# simple-phonetics
Template for REST webservice with spring

## Tecnologies

* Java 8
* Spring Boot
* Maven 3
* Release plugin
	* FindBugs plugin
	* JUnit

## Builds

To generate local builds with maven:
```bash
mvn clean install
```

To generate versioned builds for production and homologation enviroments:
```
mvn release:clean
mvn release:prepare
```

## Run
Find the Phonetics.class file then run:
```
java (string list separated by space) < (input file .txt with a list of word separated by break-line)
```