# Demo Three - Multi-Staged Docker Image Build

This demo showed how you can split your docker image layers using multipe instances of the `FROM` command.

The reason someone would do this is to utilize SDK tools for a portion of the image build, but not deploy the *production* version of the image with the bloat of including the SDK.

In this example, we build our application from the SDK docker image, and then copy the publish output to a docker image bulit from the runtime image, thus only including the runtime in the *production* version of the final image.

There really is no need to perform this demo, as it more showcased a use-case for multiple `FROM` commands in a Dockerfile.
