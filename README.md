# Veres One Documentation

Documentation for the [Veres One][] Project.

## Tool Installation

This site uses [MkDocs][] and [Material for MkDocs][].

It is *highly* recommended to setup a Python [virtual environment][] to install
the doc tools.  You can install globally also.

In your development environment, install the tools:

    $ pip install -r requirements.txt

## Development

Site source files are in the [docs](./docs) directory.

Verify your changes with the [MkDocs][] development server:

    $ mkdocs serve

## Deploy

To build and deploy to the `gh-pages` branch use the following:

    $ mkdocs gh-deploy

Changes should shortly appear on the [Veres One][] site.

[Material for MkDocs]: https://squidfunk.github.io/mkdocs-material/
[MkDocs]: http://www.mkdocs.org/
[Veres One]: https://veres.one/
[virtual environment]: https://docs.python.org/3/tutorial/venv.html
