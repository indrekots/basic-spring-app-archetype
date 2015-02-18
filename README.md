# Basic Spring 4 app maven archetype

## Summary

This archetype builds a very simple Spring 4 application

**Project contains**:
- No xml setup
- Dependency injection
- JUnit test with SpringJUnit4ClassRunner

## Installation

Install archetype into local repository

```bash
git clone https://github.com/indrekots/basic-spring-app-archetype.git
cd basic-spring-app-archetype/
mvn clean install
```
Create new project based on archetype
```bash
mvn archetype:generate \
        -DarchetypeGroupId=io.indrek \
        -DarchetypeArtifactId=basic-spring-app \
        -DarchetypeVersion=1.0.0 \
        -DgroupId=my.groupid \
        -DartifactId=my-artifactId \
        -Dversion=version
```


