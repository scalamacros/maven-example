An example Maven project which uses macros (Scala 2.10, scala-maven-plugin 3.1.0)

To verify that everything works fine, do `mvn compile`. I also almost made it runnable with `mvn run`. If you could help me with that, I'd very much appreciate it.

Note that Zinc (incremental compiler used in the Scala plugin) doesn't yet support recompilation of macro clients if macro implementation has changed: https://github.com/harrah/xsbt/issues/399.

Huge thanks to Nikita Volkov, who I've ripped off to throw together this
project: https://github.com/nikita-volkov/macros-and-maven.
