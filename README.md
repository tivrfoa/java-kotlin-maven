# Kotlin and Java in the same Maven application

## Compiling and Creating Jar file

`mvn package`

## Running the program

```sh
java -cp target/java-kotlin-maven-1.jar org.acme.Application java
Java says 'Hello World!'
java -cp target/java-kotlin-maven-1.jar org.acme.Application kotlin
Kotlin says 'Hello World!'
```

## References

https://www.baeldung.com/kotlin/maven-java-project

https://kotlinlang.org/docs/maven.html#compile-kotlin-and-java-sources
