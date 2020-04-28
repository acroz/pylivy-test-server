# pylivy Test Server

Dockerfile for testing the [pylivy](https://github.com/acroz/pylivy/) Python
client.

This Docker image is adapted from this Dockerfile provided by @ketgo:
https://github.com/acroz/pylivy/pull/60#issuecomment-582310824

## Usage

Run the Docker image with Livy's port exposed:

```sh
docker run -p 8998:8998 acroz/livy:latest
```

You can then open the Livy UI on http://localhost:8998 and run pylivy
integration tests.
