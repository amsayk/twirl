[Twirl][] is the [Play Framework][] [Scala template engine][], repackaged for stand-alone use.
This project provides an [SBT][] plugin that lets you use *Twirl* in your [Scala][] applications without any additional
dependencies on the [Play Framework][].

The [Scala template engine][] provided by Play 2.0 enables type-safe templating that integrates seamlessly into your
Scala applications. Templates are text files containing a mix of "markup" and Scala code. At compile time the
Twirl compiler translates them into actual Scala source files, which are then picked up by the Scala compiler and
compiled together with the rest of your application sources into regular .class files.
On a type level each template is just a function from a number of (strongly typed) input values to a result object.

The [Twirl][] SBT plugin smoothly integrates templating support into your Scala builds. It supports triggered
compilation (via SBTs `~` operator) as well as hot reloading via [sbt-revolver][].

  [Twirl]: https://github.com/spray/twirl
  [Play Framework]: http://www.playframework.org/
  [Scala template engine]: https://github.com/playframework/Play20/wiki/ScalaTemplates
  [SBT]: https://github.com/harrah/xsbt/wiki
  [Scala]: http://www.scala-lang.org/
  [sbt-revolver]: https://github.com/spray/sbt-revolver
