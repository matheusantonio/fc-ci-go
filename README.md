# Fullcycle - CI - Golang
A simple program in Go as an example of the use of CI in Github for the Fullcycle course

It features a simple program with a Sum function and a unit test for it. It also has an workflow to run through Github Actions which executes the unit test.

The repository was configured to require the Action to successfully execute before merging any pull request to develop or main branches.

Then, a Dockerfile was added to the project and a step to push the image to Dockerhub was added to the workflow. The repository where the image was pushed to can be found at: https://hub.docker.com/repository/docker/matheusaoc/fc-ci-go