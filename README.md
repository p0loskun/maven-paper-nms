```
.paper-nms -> .../PROJECT/.paper-nms
```

```xml
<pluginRepositories>
    ...
    <pluginRepository>
        <id>bytecode.space</id>
        <url>https://repo.bytecode.space/repository/maven-public/</url>
    </pluginRepository>
    ...
</pluginRepositories>
```

```xml
<build>
    <plugins>
        ...
        <plugin>
            <groupId>ca.bkaw</groupId>
            <artifactId>paper-nms-maven-plugin</artifactId>
            <version>1.3.2</version>
            <executions>
                <execution>
                    <phase>process-classes</phase>
                        <goals>
                            <goal>remap</goal>
                        </goals>
                </execution>
            </executions>
        </plugin>
        ...
    </plugins>
</build>
```

```xml
<repositories>
    ...
    <repository>
        <id>paper-nms</id>
        <url>https://github.com/p0loskun/maven-paper-nms/raw/main</url>
    </repository>
    ...
</repositories>
```

```xml
<dependencies>
    ...
    <dependency>
        <groupId>ca.bkaw</groupId>
        <artifactId>paper-nms</artifactId>
        <version>VERSION</version>
        <scope>provided</scope>
    </dependency>
    ...
</dependencies>
```

```xml
<version>1.19.4-SNAPSHOT</version>
```
