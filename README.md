# sbt-example [<img align="right" src="https://www.thoughtworks.com/imgs/tw-logo.png" title="ThoughtWorks" height="15"/>](http://thoughtworks.com)

[![Build Status](https://travis-ci.org/ThoughtWorksInc/sbt-example.svg)](https://travis-ci.org/ThoughtWorksInc/sbt-example)

**sbt-example** is an sbt plug-in for creating unit tests from examples in Scaladoc.

 * [Documentation](https://oss.sonatype.org/service/local/repositories/public/archive/com/thoughtworks/example/sbt-example_2.12_1.0/6.0.0/sbt-example-6.0.0-javadoc.jar/!/com/thoughtworks/Example$.html) - sbt-example eats its own dog food. The tests of sbt-example is generated by sbt-example itself from Scaladoc, which is also the documentation for using sbt-example.

The previous version of this project is the macro annotation [`@example`](https://javadoc.io/page/com.thoughtworks.example/unidoc_2.12/2.0.0/com/thoughtworks/example.html), which is [deprecated](https://github.com/scalameta/scalameta/issues/1182) and does not support Scala 2.12.5+ version.

## Showcases

* [AsynchronousPool](https://javadoc.io/page/com.thoughtworks.raii/asynchronous_2.12/latest/com/thoughtworks/raii/AsynchronousPool$.html) - an asynchronous resource pool, whose Scaladoc contains tests written in [ScalaTest](https://scalatest.org/) and [ScalaMock](https://scalamock.org)
* [Factory](https://javadoc.io/page/com.thoughtworks.feature/the_2.12/latest/com/thoughtworks/feature/Factory.html) - a dependent-type type class for dependency injection, whose Scaladoc contains a huge number of small usecases.
* [PartialApply](https://javadoc.io/page/com.thoughtworks.feature/the_2.12/latest/com/thoughtworks/feature/PartialApply.html) - a dependent-type type class for partial applying a function, whose Scaladoc is written in [Given-When-Then](https://martinfowler.com/bliki/GivenWhenThen.html) style.

(Feel free to add your Scaladoc here)

## Requirements

* Sbt 1.x
