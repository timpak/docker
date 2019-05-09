# Debian 9

## Environment Details

|Product|Version|
|:-----:|:-----:|
|Java|OpenJDK JDK 8|
|Operating System|Debian 9|
|Portal| Any bundle|

Add the test bundle to the folder before building the image.

## Startup

```sh
docker build -t <tag> .

docker run -p 8080:8080 -it <tag>:latest
```

This will start up a Liferay instance on Tomcat using HSQLDB.