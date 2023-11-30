# Trusted Certificate List

## JAVA
1. oracle
    - [jdk 1.8.0](java/jdk1.8.0.md)
    - [jdk 16](java/jdk16.md)
    - [jdk 17](java/jdk17.md)
    - [openjdk 17.35](java/openjdk-17.35.md)

1. [Temurin](https://adoptium.net/)
    - [openjdk jre 8](java/Temurin-openjdk-jre8.md)
    - [openjdk jre 11](java/Temurin-openjdk-jre11.0.21.md)
    - [openjdk 17](java/Temurin-openjdk17.0.0.9.md)

## How to get it

```bash
$ keytool -list -keystore cacerts
Enter keystore password:  changeit
```