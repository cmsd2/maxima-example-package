# Package hello-world

## Introduction to hello-world

`hello-world` is a minimal example package for the Maxima computer algebra system, demonstrating the mxpm package structure.

To use the package:

```
load("hello-world");
```

## Definitions for hello-world

### Function: hello-world_hello ()

Prints `"hello-world is loaded!"` and returns it.

Example:

```
(%i1) load("hello-world");
(%o1)                        hello-world.mac
(%i2) hello-world_hello();
hello-world is loaded!
(%o2)                   hello-world is loaded!
```

