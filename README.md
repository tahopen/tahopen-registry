# Tahopen Registry #


#### Pre-requisites for building the project:
* Maven, version 3+
* Java JDK 11

#### Building it


```
$ mvn clean install
```

#### Running the tests

__Unit tests__

This will run all tests in the project (and sub-modules).
```
$ mvn test
```

If you want to remote debug a single java unit test (default port is 5005):
```
$ cd impl
$ mvn test -Dtest=<<YourTest>> -Dmaven.surefire.debug
```
