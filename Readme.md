### Commands

Build the image

```sh
cd web
# docker build -t [app-name]:latest .
docker build -t flaskapp:latest .
```

List all images

```sh
docker images
```

This will run temporarily. Once you exit the shell, the program will stop

```
docker-compose up
```

Run an image with the id from above

```sh
# -d detach mode
docker run -d [image-id]
```
