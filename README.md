# Cloning
This repository **heavily** relies on Git submodules. You can clone 
the repository recursively to clone all submodules alongside SpamtOS.

```sh
➜ git clone --recursive https://github.com/EvrestRGB/underOS
```

If you've already cloned UnderOS, you can run this command to
clone all submodules.

```sh
➜ git submodule update --init pkg/
```

# Dependencies
UnderOS has very generic dependencies. Currently only 
[Python](https://www.python.org/), [SCons](https://scons.org/), 
and [Rust](https://www.rust-lang.org/) are necessary.

# Building
UnderOS uses [SCons](https://scons.org/) for compilation.
This resulted in building SpamtOS only taking one command.

```sh
➜ scons
```
