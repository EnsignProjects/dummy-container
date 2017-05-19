# dummy-container
The dummy-container project aims to create lightweight containers to fail or to succeed. It is possible to set a message.

This dummy-container can be used as a stub for pipelines with docker containers.

## how to run

To create a container which always succeed and prints "Custom message":

```bash
docker run -it -e MESSAGE="Custom message" ensignprojects/dummy-container
```

To create a container which returns an exit code and don't print anything:

```bash
docker run -it -e ERROR_CODE="12" ensignprojects/dummy-container
```


