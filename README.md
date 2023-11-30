# Trusted Certificate List

## JAVA
1. [Amazon](https://aws.amazon.com/ko/corretto/?filtered-posts.sort-by=item.additionalFields.createdDate&filtered-posts.sort-order=desc)
    - [corretto-9.392.08.1](java/amazon-corretto-8.392.08.1.md)
1. Oracle
    - [jdk 1.8.0](java/jdk1.8.0.md)
    - [jdk 16](java/jdk16.md)
    - [jdk 17](java/jdk17.md)
    - [openjdk 17.35](java/openjdk-17.35.md)

1. [Eclipes](https://adoptium.net/)
    - [openjdk jre 8](java/Temurin-openjdk-jre8.md)
    - [openjdk jre 11](java/Temurin-openjdk-jre11.0.21.md)
    - [openjdk 17](java/Temurin-openjdk17.0.0.9.md)

## How to get it

```bash
$ keytool -list -keystore cacerts
Enter keystore password:  changeit
```