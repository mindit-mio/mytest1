# Dagger Test

This is a sample project


## Delivering the Project

To deliver this project, you need to:

* build the Java software (using gradle)
* do a code analysis using CodeQL
* package the Java software into a container image (using docker)


## Using the Image
```bash
$ docker run -it IMAGENAME /app/mytest1-0.1/bin/mytest1

2024-04-01T07:24:43.641 [INFO] io.micronaut.context.DefaultApplicationContext$RuntimeConfiguredEnvironment - Established active environments: [cli]
Hi from mytest1!
```
