# docker
This repo coantains examples of Docker.

1. <h3>cmd-test</h3>

The purpose of this example is to demonstrate the working of <b>Dockerfile</b> commands.
In the src folder of this example, is a java file named <b>Adder.java</b>. It receives two integers as command line
arguments and displays their sum.
To execute this class in a Docker container, a Dockerfile is created. This docker file uses, CMD command to provide
default arguments. Values of these arguments can be overridden when the image is executed in a docker container.
