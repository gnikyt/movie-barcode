# Movie Barcode

This is a simple script which uses ffmpeg and ImageMagick to create a simple and neat colorful image which reprecents the movie.

## Requirements

+ ffmpeg
+ ImageMagick

If you do not have these commands, [Homebrew](http://brew.sh) makes it easy to install.

## Installation

1. Clone this repository
2. Make `movie-barcode` an executable via `chmod +x movie-barcode`
3. Enjoy!

## Usage

`./movie-barcode [PATH_TO_MOVIE] [FRAMES_TO_EXRACT=2000] [OUTPUT_FILENAME=$MOVIE_BASENAME]`

## Sample

**Movie: Scarface (1983)**

`./movie-barcode "$HOME/Movies/Scarface (1983).mp4" 2000`

![Movie Barcode of Scarface](https://raw.githubusercontent.com/tyler-king/movie-barcode/master/samples/scarface.jpg)

Would output a file named `Scarface_(1983).mp4.jpg` in the same directory as the movie-barcode executable.

**Music: DMX - I Don't Dance**

`movie-barcode.sh "$HOME/Downloads/DMX - I Dont Dance.mp4" 2000 i_dont_dance.jpg`

![Movie Barcode of DMX](https://raw.githubusercontent.com/tyler-king/movie-barcode/master/samples/dmx.jpg)

Would output a file named `i_dont_dance.jpg` in the same directory as the movie-barcode executable.

## Output

    --- Movie Barcode Generator ---
    Movie: I Don't Dance (Video) - DMX.mp4
    Frames: 2000
    Movie duration: 230.248333
    FPS extraction: 1/.11512416650000000000

    1. Extracting frames...
    Extraction complete!

    2. Resizing images...
    Resizing complete!

    3. Creating final image...
    Movie barcode created (barcode.jpg)!