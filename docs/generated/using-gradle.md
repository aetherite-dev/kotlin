# Using Gradle

[kotlin-gradle-docs]: https://kotlinlang.org/docs/reference/using-gradle.html

First, to set up Kotlin in your `build.gradle`, follow the Kotlin guide [here][kotlin-gradle-docs]. Only continue this guide once you've completed that setup.

Because `dev.aetherite.kotlin` is hosted on Maven Central, you only have to add `mavenCentral()` to your `repositories` block in your `build.gradle`:

```gradle
repositories {
  // ...
  mavenCentral()
}
```

Next, add `dev.aetherite.kotlin` as a `compileOnly` dependency to your `dependencies` block in your `build.gradle`:

```gradle
dependencies {
  // ...
  compileOnly 'dev.aetherite:kotlin:1.4.30'
}
```

That's it! Assuming you did everything correctly, you can now develop Minecraft plugins in Kotlin with ease using Gradle!
