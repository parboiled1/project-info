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

## Current status

The main project is [grappa](https://github.com/fge/grappa). It supersedes the two other
repositories that are:

* [parboiled-core](https://github.com/parboiled1/parboiled-core),
* [parboiled-java](https://github.com/parboiled1/parboiled-java).

Note that unlike parboiled-core and parboiled-java, **grappa works with Java 8**.

## Contributing

In any way you can:

* open an [issue](https://github.com/parboiled1/project-info/issues) to request a feature;
* fork and contribute to the projects above.

If you are interested, you can also ask to [join this organization](https://github.com/parboiled1).

If you use IRC, you can also join channel `#parboiled1` on [FreeNode](http://freenode.net) (server:
`irc.freenode.net`).

## Plans

See [here](https://github.com/parboiled1/project-info/wiki/Future-plans).

## Versions of old artifacts

Artifacts of **1.1.17-beta.2** are available on Maven Central. See
[here](https://github.com/parboiled1/project-info/wiki/ChangeLog) for the
changelog. Substitute `xxx` and `myVersion` below with the package and version
you need (you probably want `java` for `xxx`; it will pull `-core`
automatically):

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

