# reactive-moon

> **gmodproj >= 0.4.0**

## Description

A platform-independent Lua library, providing primitives for constructing reactive code and frameworks

## Documentation

Currently missing a more readable form of documentation, although everything under the `src` directory annotated.

## Installation

If wanting to use with a standard Lua platform, download the latest `reactive-moon.lua` build from [Releases](https://github.com/novacbn/reactive-moon/releases). And use it as you would any other library.

Alternatively, if using with `gmodproj`. Download the latest `.zip` or `.tar.gz` archive from the [Releases](https://github.com/novacbn/reactive-moon/releases). Extract the contents of `src` directory into your project's `packages` directory under a `novacbn/reactive-moon` directory.

## Building

```bash
# Clone the repository
git clone https://github.com/novacbn/novautils

# Move into the project and make the build directory
cd reactive-moon
mkdir ./dist

# Building the project will produce `./dist/reactive-moon.lua`
gmodproj build # Or gmodproj build production
```

## References

[svelte/rfcs](https://github.com/sveltejs/rfcs) - Heavily inspired by the RFCs for Svelte 3.0