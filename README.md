# Jenkins with Blue Ocean and Docker Pipeline

Image for use of jenkins with [DinD](https://hub.docker.com/_/docker) for Docker agents.

## Installed plugins

- Blue Ocean (blueocean)
- Docker pipeline (docker-workflow)

## Recommended usage

Port exposed are 8080 and 50000 for usage with DinD.

Mount shared volumes for /certs/client (read only) and /var/jenkins_home .

## Further reading

See https://www.jenkins.io/doc/tutorials/build-a-multibranch-pipeline-project/