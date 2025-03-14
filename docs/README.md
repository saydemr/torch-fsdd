# Documentation

This directory contains the Sphinx documentation for TorchFSDD.

## Viewing the documentation

You can view the documentation for different versions of TorchFSDD on [Read The Docs](https://torch-fsdd.readthedocs.io/en/latest).

## Building the documentation

To build the documentation, you'll need to make sure you have the required dependencies installed.

Once you've cloned the repository, you can do this by running the following command in the repository root.

```console
pip install .[dev]
```

Once the dependencies are installed, you can build the documentation with the following command (from the `docs` directory).

```console
sphinx-autobuild . _build/html --watch ../src
```

This will pick up any changes made to the `docs` and `src` directories and restart the Sphinx server.
