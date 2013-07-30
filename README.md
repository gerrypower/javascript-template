# Template Javascript Project

## <a name="introduction"></a>Introduction
This is a Javascript template project using [bundler](http://bundler.io),
[guard](https://github.com/guard/guard) and [livereload](http://livereload.com)
with [Jasmine](http://pivotal.github.io/jasmine/)
to automatically compile and reload all assets as they change, and automically run
the Jasmine tests. It is setup to automatically compile [Coffescript](http://coffeescript.org),
but can be used for a Javascript only project with some changes to the .gitignore.

Note: Livereload is embedded in the spec runner, and no browser extensions are required.

### Install

Prerequisites: ruby and bundler installed

Fork it, and run:

```console
bundle
bundle exec guard
```
