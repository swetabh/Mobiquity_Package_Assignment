# Mobiquity_Package_Assignment
Mobiquity Package Assignment


This project is a simple Java Based application applying the business conditions which as per the assignment.

Note: In order to run the project, kindly download the source code and run the code as mvn clean install 

#####Assumptions:
Currently I assumed that a maximum of 2 items can be selected for packaging 
 
For building and running the application you need:

- [JDK 1.8+](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven 3](https://maven.apache.org)

## Approach Discussion
Its a stand-alone application consist of all Possible test cases. Following are the approach has been taken to address this assignment

1. Each package detail is segregated as an entity and can be part of the calculation if it satisfies the condition.
2. Designed in a way that each combination can be tested separately.


## How to Run
```shell
mvn clean test
```
## How to get Coverage
```shell
mvn clean install
```
it will generate coverage reports in mobiquity\target\site\jacoco
Open index.html
