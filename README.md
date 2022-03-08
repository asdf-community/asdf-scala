# asdf-scala

This is Scala plugin for asdf version manager.
Install script was adapted from https://github.com/smashedtoatoms/asdf-scala/blob/master/bin/install

# Dependencies

To run Scala, you need to have a working Java install (either Oracle's or OpenJDK).

# Install

Plugin:

```shell
asdf plugin add scala
# or
asdf plugin add scala https://github.com/asdf-community/asdf-scala
```

scala:

```shell
# Show all installable versions
asdf list-all scala

# Install specific version
asdf install scala latest

# Set a version globally (on your ~/.tool-versions file)
asdf global scala latest

# Now scala commands are available
scala -help
```
