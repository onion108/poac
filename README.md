<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/26405363/170157214-51b03bbd-cd29-432b-99ca-8f65c01f973e.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/26405363/170157184-e338188c-e4fa-4967-ac74-aba03aefa0bc.svg">
    <img alt="Poac Logo" width="250" src="https://user-images.githubusercontent.com/26405363/170157184-e338188c-e4fa-4967-ac74-aba03aefa0bc.svg">
  </picture>
</div>

> [!WARNING]
> The information here may vary depending on the version you are using.  Please refer to the corresponding `README.md` by visiting the Git tag corresponding to your version, e.g., https://github.com/poac-dev/poac/blob/0.9.3/README.md.  Running `poac version` will provide you with the current version.

## Description

> [!CAUTION]
> Poac is still under development and may contain a bunch of bugs.

![demo](https://vhs.charm.sh/vhs-5dQzA2VI3B0e4jTAC6RrME.gif)

Poac (pronounced as `/pəʊək/`) is a package manager and build system for C++ users, inspired by Cargo for Rust.  Poac is designed as a structure-oriented build system, which means that as long as you follow Poac's designated project structure, you almost do not need configurations, much less a language to build, unlike CMake.  If you do not like writing a bunch of configurations to build your project, Poac might be best suited.  Currently, the supported project structure can be known by looking at this repository since Poac can build itself.

Please visit [poac.dev](https://poac.dev) and [Poac Docs](https://poac.dev/docs) for more details.

## Hello World

You can get started with just a few commands as the demo shows. Let's create a new Poac project:

```console
you:~$ poac new hello_world
     Created binary (application) `hello_world` package
```

Now, you can use the `poac run` command to run your application:

```console
you:~$ cd hello_world
you:~/hello_world$ poac run
 Compiling src/main.cc
   Linking hello_world
  Finished debug target(s) in 0.45386s
   Running poac-out/debug/hello_world
Hello, world!
```

## Installation

Read ["Installation"](https://poac.dev/docs/installation) from [Poac Docs](https://poac.dev/docs).

## Installing from Source

Although building from source is not recommended, if you really want to do so, see [INSTALL.md](INSTALL.md).

## Community

See [GitHub Discussions](https://github.com/orgs/poac-dev/discussions).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

Poac is licensed under the terms of the Apache License version 2.0.

Please see [LICENSE](LICENSE) for details.

### Third-party software

* toml11 - <https://github.com/ToruNiina/toml11/blob/master/LICENSE>


[^1]: Amemiya, T., & Mizutani, S. (2006). On the Basic Affective Dimensions of Japanese Onomatopoeia and the Basic Level of Japanese Phonesthemes. 関西大学社会学部紀要, 37(2), 139–166. https://hdl.handle.net/10112/12311
