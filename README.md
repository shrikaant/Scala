# Scala
#Below are the steps to install Lightbend activator.
Install jdk and set path
download playframework activator
https://www.playframework.com/documentation/2.5.x/Installing
Install sbt
http://www.scala-sbt.org/0.13/docs/Installing-sbt-on-Mac.html
In activator.bat file change below line
set SBT_HOME=%BIN_DIRECTORY
to
set SBT_HOME=%BIN_DIRECTORY%

Search the new templates on http://127.0.0.1:8888/home
and then code build and run them in activator ui.


On cmd type activator ui
The lightbend activator provides a ui to write scala and code, to build it,
it calls sbt.
