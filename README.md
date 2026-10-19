# docker-ubuntu-desktop
Ubuntu Docker image with SSHX terminal sharing.

## Usage
```
$ docker run -it --rm --platform=linux/amd64 docker-ubuntu-desktop
```

SSHX prints a sharing URL in the terminal. Open that URL to access the shared terminal. Anyone with the URL may be able to access the session, so treat it as sensitive.

## DockerHub

https://hub.docker.com/r/akarita/docker-ubuntu-desktop

## Docker Pull
```
$ docker pull akarita/docker-ubuntu-desktop
```

To run the published image:
```
$ docker run -it --rm --platform=linux/amd64 akarita/docker-ubuntu-desktop
```

## Docker Build
```
$ docker build . -t docker-ubuntu-desktop
```

## License
MIT License (c) 2023 [Takahashi Akari](https://github.com/takahashi-akari)
