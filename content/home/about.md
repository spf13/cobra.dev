---
title: "About"
image: "logo.png"
weight: 10
---

Cobra is a CLI framework for Go. It contains a library for creating powerful modern CLI applications and a tool to rapidly generate Cobra based applications and command files.

It was created by Go team member, [spf13](https://twitter.com/spf13) for [hugo](https://gohugo.io) and has been adopted by the most popular Go projects.

### Cobra provides:

* Easy subcommand-based CLIs: `app server`, `app fetch`, etc.
* Fully POSIX-compliant flags (including short & long versions)
* Nested subcommands
* Global, local and cascading flags
* Easy generation of applications & commands with `cobra init appname` & `cobra add cmdname`
* Intelligent suggestions (`app srver`... did you mean `app server`?)
* Automatic help generation for commands and flags
* Automatic help flag recognition of `-h`, `--help`, etc.
* Automatically generated bash autocomplete for your application
* Automatically generated man pages for your application
* Command aliases so you can change things without breaking them
* The flexibility to define your own help, usage, etc.
* Optional tight integration with [viper](http://github.com/spf13/viper) for 12-factor apps
