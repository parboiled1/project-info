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

Based on a [fork of the original repository](https://github.com/parboiled1/parboiled), the following
has been achieved so far:

* split of the [core package](https://github.com/parboiled1/parboiled-core), the [Java
  package](https://github.com/parboiled1/parboiled-java) and the [Java examples
  package](https://github.com/parboiled1/parboiled-examples);
* switch of the build system from sbt to [Gradle](http://gradle.org).

No artifacts have been published as of yet. **Note that you MUST use either a JDK 6 or 7, JDK 8 will
not work at this moment.**

## Contributing

In any way you can:

* open an [issue](https://github.com/parboiled1/project-info/issues) to request a feature;
* fork and contribute to the projects above.

If you are interested, you can also ask to [join this organization](https://github.com/parboiled1).

## Plans

Good question...

First of all, probably publish the javadoc on Github (using the dedicated `gh-pages` branch). Then,
in no particular order:

* drop Java 6 support; take advantage of Java 7's [invokedynamic (aka
  "indy")](http://blog.headius.com/2008/09/first-taste-of-invokedynamic.html);
* write more examples;
* document the inner workings.

And so on. Do not hesitate to make suggestions, of course.
