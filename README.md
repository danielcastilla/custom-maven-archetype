# How to create a Maven Archetype



## Directory structure

```
archetype
|  pom.xml
|__src
    |__main
        |__resources
            |__META-INF
            |   |__maven
            |       |__archetype-metadata.xml
            |__archetype-resource
                |__pom.xml
                |__src
                    |__main
                        |__java
                    |__test
                        |__java
```



#### Archetype Resource

Archetype-resources folder contain your prototype project.