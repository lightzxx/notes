* Gradle is like gem in ruby.

* Add dependency is just to write script.

```
apply plugin: 'java'
apply plugin: 'jacoco'

version = '1.0'

repositories {
    mavenCentral()
}

dependencies {
    testCompile group: 'junit', name: 'junit',
            version: '4.11'
    testCompile group: 'pl.pragmatists', name: 'JUnitParams', version: '1.0.5'
}
```
