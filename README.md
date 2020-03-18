# Static site using nginx

To build a Docker image from the Dockerfile, run the following command from inside this directory

```sh
$ docker build -t <docker-hub-username>/static-site:1.0 .
```

To run the image in a Docker container
```sh
$ docker run -itd --name mycontainer --publish 8080:80 <docker-hub-username>/static-site:1.0
```

