# Cowsay
Generates an ASCII pictures of a cow (or other charcter) with a message.

## Cowsay (Project Info)
[Website](https://en.wikipedia.org/wiki/Cowsay)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/cowsay/)

## Build image
`$ docker build -t macabees/cowsay:latest .`

## Docker Push
`$ docker push -t macabees/cowsay:latest`

Note: requires `docker login`

## Run image
`$ echo "Hello World" | docker run -i --rm macabees/cowsay --`

 --OR--

`$ docker run -it --rm macabees/cowsay "Hello World"`

--OR--

`$ docker run -it --rm macabees/fortune | docker run -i --rm macabees/cowsay --`

## Help
`$ docker run -it --rm macabees/cowsay -h`
