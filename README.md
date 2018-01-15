# docker-project
A Docker / NodeJS  environment project

## Simple Application using this container
For better example using this technique, checkout [this exercise using a docker container to improve the server installation](https://github.com/alexmontdor/touch-screen)

## Possible Issues

When setting up the docker container, the system may display an error

Example:

docker: Error response from daemon: oci runtime error: container_linux.go:262: starting container process caused "exec: \"/app/scripts/dev_entrypoint.sh\": permission denied".

The fix is to change the mode of execution of the file

src/server/scripts> chmod +x dev_entrypoint.sh


## References
[The Ultimate NodeJS Development Setup with Docker](http://paislee.io/the-ultimate-nodejs-development-setup-with-docker/) - Use this blog

