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

`movie-barcode.sh [PATH_TO_MOVIE] [FRAMES_TO_EXRACT=2000]`

## Sample

**Movie: Scarface (1983)**

`movie-barcode.sh "$HOME/Movies/Scarface (1983).mp4" 2000`

![Movie Barcode of Scarface](https://raw.githubusercontent.com/tyler-king/movie-barcode/master/samples/scarface.jpg)

**Music: DMX - I Don't Dance**

`movie-barcode.sh "$HOME/Downloads/DMX - I Dont Dance.mp4" 2000`

![Movie Barcode of DMX](https://raw.githubusercontent.com/tyler-king/movie-barcode/master/samples/dmx.jpg)

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