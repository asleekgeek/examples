Building the meteor-kubernetes base image
-----------------------------------------

As a normal user you don't need to do this since the image is already built and pushed to Docker Hub. You can just use it as a base image. See [this example](https://github.com/Q42/meteor-gke-example/blob/master/Dockerfile).

To build and push the base meteor-kubernetes image:

    docker build -t chees/meteor-kubernetes .
    docker push chees/meteor-kubernetes

