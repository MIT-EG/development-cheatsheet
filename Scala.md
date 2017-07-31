Starting development with Scala

Scala (www.scala-lang.org) is a language created over the JVM (Java Virtual Machine). To start development:
- install Oracle JDK (Java Development Kit)
- install Scala

To orchestrate the compilation of your project, usage of SBT (Simple Build Tool) is advised:
- install sbt

For an IDE Jetbrains Idea Community Edition (which is free) is suggested:
- download and install Jetbrains Toolbox
- select and install IDEA Community Edition

When you first launch IDEA select and install the Scala plugin at featured plugins.

To create a new Scala project, select "Create new project", and choose Scala and SBT. Give a name and directory for your project.

When the project is opened, enable auto-import, thus modifying the project build file will automatically refresh the project structure.

Your project structure should look similarly:
src/main/scala -> here will you put your Scala source files
src/test/scala -> code tests should go here
build.sbt -> the build description file
