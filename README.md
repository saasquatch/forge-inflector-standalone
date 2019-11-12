# forge-inflector-standalone

[![License](https://img.shields.io/badge/License-EPL%201.0-red.svg)](https://opensource.org/licenses/EPL-1.0)
[![Build Status](https://travis-ci.org/saasquatch/forge-inflector-standalone.svg?branch=master)](https://travis-ci.org/saasquatch/forge-inflector-standalone)
[ ![Download](https://api.bintray.com/packages/saasquatch/java-libs/forge-inflector-standalone/images/download.svg) ](https://bintray.com/saasquatch/java-libs/forge-inflector-standalone/_latestVersion)
[![javadoc.io](https://javadoc.io/badge2/com.saasquatch/forge-inflector-standalone/javadoc.io.svg)](https://javadoc.io/doc/com.saasquatch/forge-inflector-standalone)

Standalone Inflector.java from [JBoss Forge](https://github.com/forge)

Pulled from [the original source of JBoss Forge](https://github.com/forge/core/blob/223ea7fd6b53951787f778e48b3507b1da6e87e9/text/src/main/java/org/jboss/forge/addon/text/Inflector.java) with slight modifications, licensed under [EPL v1.0](https://www.eclipse.org/legal/epl-v10.html).

## Adding to your project

### Add the repository

Maven

```xml
<repositories>
  <repository>
    <id>jcenter</id>
    <url>https://jcenter.bintray.com/</url>
  </repository>
</repositories>
```

Gradle

```gradle
repositories {
  jcenter()
}
```

### Add the dependency

Maven

```xml
<dependency>
  <groupId>com.saasquatch</groupId>
  <artifactId>forge-inflector-standalone</artifactId>
  <version>1.0.1</version>
</dependency>
```

Gradle

```gradle
compile 'com.saasquatch:forge-inflector-standalone:1.0.1'
```
