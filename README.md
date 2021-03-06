# Slang Compiler

A project to create a compiler in OCAML for CSC312

## Getting Started

Simply download the repo as a zip and run the MAKEFILE.

In addition, to enable git hooks, create a Symbolic link between the pre-commit file in githooks/ and .git/hooks/ using the command below.

```
ln -s githooks/ .git/hooks/
```

### Prerequisites

You will need OCAML but no accompanying libraries. You will also need a Linux distro or appropriate UNIX-like OS capable of running bash scripts.

```
apt-get install ocaml-nox # If you don't want X11 support.
apt-get install ocaml

pacman -S ocaml

brew install ocaml
brew install opam
```

## Running the tests

The testing suite can be accessed by running

```
make test
```

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **Yash Gupta**

See also the list of [contributors](https://github.com/yashdavisgupta/Slang/graphs/contributors) who participated in this project.

## License

This project is licensed under the GPL V.3 License - see the [LICENSE.md](LICENSE.md) file for details
