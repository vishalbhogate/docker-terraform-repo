## Dependencies
- Docker

## Docker

#### Build
Now you are ready to build an image from this project Dockerfile.
```bash
docker build -t docker-terraform .
```

#### Run

After your image has been built successfully, you can run it as a container.

```bash
docker run docker-terraform --help
docker run docker-terraform <command>
```