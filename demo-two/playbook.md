# Demo Two - Building our own Docker Image

In this demo, I demonstrate how we can build our own docker image of a hello-world application written in Python.

```bash
# Build and tag the docker image
docker build -t flask-hello-world:latest .

# Run the docker image we've just built
docker run -p 5000:5000 flask-hello-world:latest
```
