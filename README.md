# Henshin Interpreter (repackaged for Maven)
This repository contains the version 1.4.0 of the [Henshin](https://www.eclipse.org/henshin) interpreter. We used Gradle here to repackage the library (with source and javadoc jars) for maven and to publish it to Maven central. We need the interpreter not only within Eclipse but within our standalone library as well.

## Using the Library
We published the interpreter to Maven central, so you can use it within your Maven or Gradle build:

**Gradle:**
```gradle
implementation 'org.contextmapper:henshin-interpreter:1.4.0'
```

**Maven:**
```xml
<dependency>
  <groupId>org.contextmapper</groupId>
  <artifactId>henshin-interpreter</artifactId>
  <version>1.4.0</version>
</dependency>
```

## Original Source Repository
The original source repo: https://git.eclipse.org/c/henshin/org.eclipse.emft.henshin.git/
We have not changed any code of the Henshin developers. We just packaged and published it as Maven artifact.

Find information about Henshin here: https://www.eclipse.org/henshin
