# Maven-Repository

This is a Maven repository providing artifacts for our projects hosted on GitHub.
It should be obsolete when public GitHub Packages can be read without authentication.

Add this to your `pom.xml` to access the artifacts hosted here:
```xml
  <repositories>
    <repository>
      <id>github</id>
      <url>https://raw.githubusercontent.com/DFKI-MLT/Maven-Repository/main</url>
    </repository>
  </repositories>
```
