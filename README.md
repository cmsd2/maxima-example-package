# hello-world

[![Docs](https://img.shields.io/badge/docs-GitHub%20Pages-blue)](https://cmsd2.github.io/maxima-example-package/)

TODO: Describe what this package does.

## Install

Install locally during development:

```
mxpm install --path . --editable
```

Or copy-install:

```
mxpm install --path .
```

## Usage

```maxima
load("hello-world");
hello_world_hello();
```

## Documentation

Build documentation artifacts (`.info` and help index):

```
mxpm doc build
```

Live preview with mdBook:

```
mxpm doc serve
```

## License

MIT
