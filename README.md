# aws-lambda-java-template

![](https://github.com/zero-templates/aws-lambda-java-template/workflows/aws-lambda-java-template-ci/badge.svg)

This is java aws-lambda-java template. This template allows to build AWS lambda seamlessly.

## Developing

Below command will generate the distribution zip under `build/distributions/{app_name}.zip`.

```shell script
$ ./gradlew [Targets]
```

### **Targets**

- `$ ./gradlew clean`

    Clean the previous generated builds.

- `$ ./gradlew build`

    Compile the classes and generate build.
    Build can be found under `build/libs/{app_name}.jar` directory.

## Overview

- **Maintainer**: mishalshah92@gmail.com