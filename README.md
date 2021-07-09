# Lundegaard build tools support

This project contains resources for different build tools. It is mainly used as a dependency for Maven plugins, e.g. like this

```xml
<plugin>
    <groupId>com.mycila</groupId>
    <artifactId>license-maven-plugin</artifactId>
    <version>3.0</version>
    ...
    <configuration>
        <header>licenses/lundegaard-lgpl-notice.txt</header>
        ...
    </configuration>
    <dependencies>
        <dependency>
            <groupId>eu.lundegaard.commons</groupId>
            <artifactId>build-support</artifactId>
            <version>${lundegaard.build.support.version}</version>
        </dependency>
    </dependencies>
</plugin>
```
