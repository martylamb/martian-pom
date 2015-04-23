# martian-pom

Common parent pom for multiple martiansoftware.com projects.

To use, add the following to the project pom (you really don't need this if you're not building a new martiansoftware.com project).

```xml
<parent>
    <groupId>com.martiansoftware</groupId>
    <artifactId>martian-pom</artifactId>
    <version>1.0.0-SNAPSHOT</version>       
</parent>

<repositories>
    <repository>
        <id>martiansoftware</id>
        <url>http://mvn.martiansoftware.com</url>
    </repository>
</repositories> 
```

