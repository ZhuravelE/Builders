## Build Instructions - Maven

To build the project using Maven, run the following command from the root directory:
```shell
mvn clean install
```

This will compile the code, run tests, and generate the necessary artifacts.

To build a specific module, navigate to the module directory and run the same Maven command.

To run tests only, use the following command:
```shell
mvn test
```


## Build Instructions - Gradle

To build the project using Gradle, run the following command from the root directory:
```shell
gradle clean build
```


This will compile the code, run tests, and generate the necessary artifacts.

To build a specific module, navigate to the module directory and run the same Gradle command.

To run tests only, use the following command:
```shell
gradle test
```

After building the project, you will find the generated artifacts in the respective project directories:
- `admin.jar` in the `admin` project directory.
- `web.war` in the `web` project directory.

Please refer to the individual project directories for more information about each module.


Change 1