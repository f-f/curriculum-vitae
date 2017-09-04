# My Curriculum Vitae

## How To

1. Install [Docker](https://www.docker.com/)
2. Clone this repo
3. Run `./latex-build lualatex cv.tex`

## Switching fonts

By default the CV uses `Montserrat` and `Montserrat Bold` fonts.  
Since the entirety of [Google Fonts](https://fonts.google.com/) is included in the docker image,
switching to any of them should be easy.

However, to be sure about the name that the GFont name has on the system, you can use `./latex-build fc-list | grep $YOUR_FONT_NAME`.
