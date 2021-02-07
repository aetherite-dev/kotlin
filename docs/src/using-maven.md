[maven-central-badge]: https://img.shields.io/maven-central/v/dev.aetherite/kotlin?logo=Apache&style=flat-square&label=release
[maven-central-url]: https://search.maven.org/artifact/dev.aetherite/kotlin/${version}/jar

# Using Maven [![Maven Badge][maven-central-badge]][maven-central-url]

[kotlin-maven-docs]: https://kotlinlang.org/docs/reference/using-maven.html

First, to set up Kotlin in your `pom.xml`, follow the Kotlin guide [here][kotlin-maven-docs]. Only continue this guide once you've completed that setup.

Because `dev.aetherite.kotlin` is hosted on Maven Central, you don't have too add any additional repositories. Just add the following dependency to your `dependencies` field in your `pom.xml`:

```xml
<dependency>
  <groupId>dev.aetherite</groupId>
  <artifactId>kotlin</artifactId>
  <version>${version}</version>
</dependency>
```

That's it! Assuming you did everything correctly, you can now develop Minecraft plugins in Kotlin with ease using Maven!
