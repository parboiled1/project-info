## What this is

[Parboiled](https://github.com/sirthias/parboiled) is a great software package which allows you to
create parsers for arbitrary DSLs of your choice **entirely in Java**. No preprocessing phase is
needed, unlike with, for instance, JavaCC or Antlr.

[Parboiled2](https://github.com/sirthias/parboiled2) is its successor. Unfortunately for Java people
who don't do Scala, Parboiled2 will be Scala only.

This GitHub organization is therefore dedicated to continue the development of
what is called here parboiled1. A discussion as to the relevance of such an
organization has occurred on the [parboiled users
group](http://users.parboiled.org/Parboiled-quot-1-quot-status-as-of-today-Possibility-of-a-fork-td4024289.html),
and here we are.

The license is unchanged: Apache Software License, version 2.

## Version

The current version is **1.1.17-beta.2**. See
[here](https://github.com/parboiled1/project-info/wiki/ChangeLog) for the changelog. Parboiled
requires Java 6 to run, but see below.

These artifacts are available on Maven. Substitute `xxx` and `myVersion` below with the package and
version you need (you probably want `java` for `xxx`; it will pull `-core` automatically):

```
// Using gradle...

dependencies {
    compile(group: "com.github.parboiled1", name: "parboiled-xxx", version: "myVersion");
}

// Using maven:

<dependency>
    <groupId>com.github.parboiled1</groupId>
    <artifactId>parboiled-xxx</artifactId>
    <version>myVersion</version>
</dependency>
```

## Current status

Based on a [fork of the original repository](https://github.com/parboiled1/parboiled), the following
has been achieved so far:

* split of the [core package](https://github.com/parboiled1/parboiled-core), the [Java
  package](https://github.com/parboiled1/parboiled-java) and the [Java examples
  package](https://github.com/parboiled1/parboiled-examples);
* switch of the build system from sbt to [Gradle](http://gradle.org);
* no more Scala support (you want to use
  [parboiled2](https://github.com/sirthias/parboiled2) instead).

**Note that you MUST use either a JDK 6 or 7, JDK 8 will not work at this moment.**

## Contributing

In any way you can:

* open an [issue](https://github.com/parboiled1/project-info/issues) to request a feature;
* fork and contribute to the projects above.

If you are interested, you can also ask to [join this organization](https://github.com/parboiled1).

If you use IRC, you can also join channel `#parboiled1` on [FreeNode](http://freenode.net) (server:
`irc.freenode.net`).

## Plans

See [here](https://github.com/parboiled1/project-info/wiki/Future-plans).

