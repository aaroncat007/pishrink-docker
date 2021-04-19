# PiShrink Docker

See 
https://github.com/Drewsif/PiShrink

## Usage

In the directory containing `<your-image>.img`:

bash:
    docker build -t pishrink .
    docker run --rm --privileged=true -v ${PWD}:/workdir pishrink pishrink <your-image>.img

