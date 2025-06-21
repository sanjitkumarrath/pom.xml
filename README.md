4.0.0 devops suneel 1.0-SNAPSHOT war suneel Maven Webapp http://www.example.com UTF-8 17 17 junit junit 4.13.1 test suneel maven-clean-plugin 3.4.0 maven-resources-plugin 3.3.1 maven-compiler-plugin 3.13.0 maven-surefire-plugin 3.3.0 maven-war-plugin 3.4.0 maven-install-plugin 3.1.2 maven-deploy-plugin 3.1.2
This XML file does not appear to have any style information associated with it. The document tree is shown below.
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
<modelVersion>4.0.0</modelVersion>
<groupId>devops</groupId>
<artifactId>suneel</artifactId>
<version>1.0-SNAPSHOT</version>
<packaging>war</packaging>
<name>suneel Maven Webapp</name>
<!-- FIXME change it to the project's website -->
<url>http://www.example.com</url>
<properties>
<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
<maven.compiler.source>17</maven.compiler.source>
<maven.compiler.target>17</maven.compiler.target>
...
</properties>
<dependencies>
<dependency>
<groupId>junit</groupId>
<artifactId>junit</artifactId>
<version>4.13.1</version>
<scope>test</scope>
...
</dependency>
...
</dependencies>
<build>
<finalName>suneel</finalName>
<pluginManagement>
<!-- lock down plugins versions to avoid using Maven defaults (may be moved to parent pom) -->
<plugins>
<plugin>
<artifactId>maven-clean-plugin</artifactId>
<version>3.4.0</version>
...
</plugin>
<!-- see http://maven.apache.org/ref/current/maven-core/default-bindings.html#Plugin_bindings_for_war_packaging -->
<plugin>
<artifactId>maven-resources-plugin</artifactId>
<version>3.3.1</version>
...
</plugin>
<plugin>
<artifactId>maven-compiler-plugin</artifactId>
<version>3.13.0</version>
...
</plugin>
<plugin>
<artifactId>maven-surefire-plugin</artifactId>
<version>3.3.0</version>
...
</plugin>
<plugin>
<artifactId>maven-war-plugin</artifactId>
<version>3.4.0</version>
...
</plugin>
<plugin>
<artifactId>maven-install-plugin</artifactId>
<version>3.1.2</version>
...
</plugin>
<plugin>
<artifactId>maven-deploy-plugin</artifactId>
<version>3.1.2</version>
...
</plugin>
...
</plugins>
...
</pluginManagement>
...
</build>
...
</project>
