UMLS Terminology Services API 2.0
=================================

Java source files imported From WSDL files according to https://uts.nlm.nih.gov/home.html#apidocumentation

Use in a Maven project
-------------------------

Configure your pom.xml by adding this repository

```xml
<repository>
  <id>ziy-mvnrepo-releases</id>
  <name>ziy GitHub Personal Repo</name>
  <url>https://raw.github.com/ziy/mvn-releases/master/</url>
</repository>
```

and adding this dependency

```xml
<dependency>
  <groupId>edu.cmu.lti.oaqa.bio</groupId>
  <artifactId>uts-api</artifactId>
  <version>0.0.2</version>
</dependency>
```