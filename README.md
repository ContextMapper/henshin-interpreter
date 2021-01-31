# Henshin Interpreter (repackaged for Maven) 
![Build](https://github.com/ContextMapper/henshin-interpreter/workflows/Build/badge.svg) [![Maven Central](https://img.shields.io/maven-central/v/org.contextmapper/henshin-interpreter.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22org.contextmapper%22%20AND%20a:%22henshin-interpreter%22)

This repository contains the version 1.6.0 of the [Henshin](https://www.eclipse.org/henshin) interpreter. We used Gradle here to repackage the library (with source and javadoc jars) for maven and to publish it to Maven central. We need the interpreter not only within Eclipse but within our standalone library as well.

## Using the Library
We published the interpreter to Maven central, so you can use it within your Maven or Gradle build:

**Gradle:**
```gradle
implementation 'org.contextmapper:henshin-interpreter:1.6.0'
```

**Maven:**
```xml
<dependency>
  <groupId>org.contextmapper</groupId>
  <artifactId>henshin-interpreter</artifactId>
  <version>1.6.0</version>
</dependency>
```

If you not only need the interpreter but the whole Henshin plugin repackaged for Maven, you may have a look at this project: https://github.com/stefan-ka/henshin-maven

## Original Source Repository
The original source repo: https://git.eclipse.org/c/henshin/org.eclipse.emft.henshin.git/
We have not changed any code of the Henshin developers. We just packaged and published it as Maven artifact.

Find information about Henshin here: https://www.eclipse.org/henshin
