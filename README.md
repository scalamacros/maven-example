An example Maven project which uses macros (Scala 2.10, scala-maven-plugin 3.1.0)

Note that Zinc (incremental compiler used in the Scala plugin) doesn't yet support recompilation of macro clients if macro implementation has changed: https://github.com/harrah/xsbt/issues/399.