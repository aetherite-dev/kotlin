<p align="right">
  <a href="https://search.maven.org/artifact/dev.aetherite/kotlin/1.4.30/jar">
    <img src="https://img.shields.io/maven-central/v/dev.aetherite/kotlin?logo=Apache&style=flat-square&label=release" alt="Maven Badge">
  </a>
  <a href="https://github.com/aetherite-dev/kotlin/releases/v1.4.30">
    <img src="https://img.shields.io/github/v/release/aetherite-dev/kotlin?logo=GitHub&style=flat-square" alt="GitHub Badge">
  </a>
</p>

<br>
<br>

<h1 align="center"><img src="https://github.com/aetherite-dev/kotlin/blob/main/docs/assets/logo.svg" width=24> Kotlin for Minecraft</h1>

<p align="center">A Minecraft plugin for Bukkit, BungeeCord, and their derivatives that enables other Minecraft plugins to easily use and distribute Kotlin v1.4.30.</p>

<br>
<br>
<br>

## Motivation

Minecraft plugin developers, when writing their plugins in Kotlin, have to bundle the Kotlin standard library into their plugin.

This plugin allows for plugin developers to no longer have to bundle the Kotlin standard library into their distribution.

Plugin developers reap the benefit of having shorter build times and plugin consumers reap the benefit of smaller plugin distributions and quicker speeds.

## Installation

[github-release-url]: https://github.com/aetherite-dev/kotlin/releases/v1.4.30
[jar-url]: https://github.com/aetherite-dev/kotlin/releases/download/v1.4.30/kotlin-1.4.30.jar

Download the latest version of this Minecraft plugin from [GitHub][github-release-url]. Or, to directly download `kotlin-1.4.30.jar`, click [here][jar-url].

## Usage

### For Consumers

Drag the downloaded `kotlin-1.4.30.jar` (downloaded in the ["Installation"](#installation) section) into your Minecraft server's `plugins` folder.

That's it! If done successfully, now all plugins on your server that utilize this plugin will function as intended.

### For Developers

[using-maven]: https://github.com/aetherite-dev/kotlin/blob/main/docs/generated/using-maven.md
[using-gradle]: https://github.com/aetherite-dev/kotlin/blob/main/docs/generated/using-gradle.md

First, resolve the plugin as a dependency to your project using either Maven or Gradle:

- Click [here][using-maven] if you're using Maven.
- Click [here][using-gradle] if you're using Gradle.

Finally, depend on the kotlin plugin in your `plugin.yml` or `bungee.yml`:

```yml
depend:
  # ...
  - kotlin
```

That's it! If done successfully, your plugin will work as intended on any Minecraft server that also has this plugin downloaded. Be sure to tell your consumers to download this plugin as a dependency!

## License

[license-url]: https://github.com/aetherite-dev/kotlin/blob/main/LICENSE.md

This plugin is available as open source under the terms of the [MIT LIcense][license-url].
