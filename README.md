# SES TDD Exercise 1

Oefening voor https://brainbaking.com/teaching/ses/

## Technologie

Java 11+, Gradle 5+, JUnit 4+. Er is nog géén project voorzien. Maak een nieuw leeg Gradle project aan, stel de juiste versies in, en voorzie de juiste dependencies in het `build.gradle` bestand.

## Opgave

### 1.1 De Calculator app

Ontwerp een command-line interface programma, getiteld 'calculator', dat twee argumenten inleest die terecht komen in de `main()` methode, en de sommatie ervan afdrukt:

`java -cp . Calculator 1 4` print `5` in `stdout`.

Uiteraard gebruiken we hier Gradle voor. Zet de berekening in een aparte methode, die ook _getest_ werd. Voorzie dus ook Enkele eenvoudige unit testen in `src/main/test`. 

### 1.2 De app builden op Travis

Nadat de code voor 1.1 werd gecommit en gepushed op je Git repository, is de volgende stap dit project automatisch te builden op een server, zoals Travis. Om dit te activeren moeten er twee stappen worden uitgevoerd:

1. Activeer je repository door op [travis-ci.org](travis-ci.org) in te loggen met je Github account, de repository terug te zoeken in de lijst door op `+` te drukken links, en de slider naar rechts te zetten, zodat Travis changes detecteert. 
2. Voorzie een `.travis.yml` bestand waarin staat beschreven op welke manier je project moet worden gebuild. 
