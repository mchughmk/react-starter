# React Starter

A Docker-based bootstrapper for a new React project.

This image uses the `create-react-app` command to create a new React app using the project name passed in as a command line parameter. Mapping a local volume to /project in the container causes the newly-created files to exist in that volume.

## Use

To use, issue the following command:
```
docker run --rm -v $PWD:/project mchughmk/react-starter project-name [options]
```