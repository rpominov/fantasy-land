This repository contains a WIP version of a specification that unifies Fantasy and Static lands.

Links:

 - [fantasy-land#199](https://github.com/fantasyland/fantasy-land/issues/199) — related issue in Fantasy Land;
 - [static-land#45](https://github.com/rpominov/static-land/issues/45) — relatad issue in Static Land;
 - [fantasyland/unified-specification](https://github.com/fantasyland/unified-specification) — repository for discussions regarding the unified specification.

--------------------------------------

# Fantasy Land Specification

[![Build Status](https://travis-ci.org/fantasyland/fantasy-land.svg?branch=master)](https://travis-ci.org/fantasyland/fantasy-land) [![Join the chat at https://gitter.im/fantasyland/fantasy-land](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/fantasyland/fantasy-land?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

(aka "Algebraic JavaScript Specification")

<img src="logo.png" width="200" height="200" />

This project specifies interoperability of common algebraic structures. The main content is in a separate document:

 - [Specification](specification.md)


### How to add compatibility with Fantasy Land to your library

If your library defines a new type make sure that the values of that type have a reference to the canonical [module](specification.md#module) in the `fantasy-land/canonical` property [as described in the specification](specification.md#canonical-module).

In rare cases when it's impossible to add the property to values, for example when you define a module for a type that you cannot control, it's still useful to expose compatible [module objects](specification.md#module). Simply say in your documentation where the modules are located.


### Compatible libraries

TODO: we probably should have a document in wiki for this.
