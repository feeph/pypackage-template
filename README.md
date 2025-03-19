# pypackage-template

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit)](https://github.com/pre-commit/pre-commit)
[![copier](https://img.shields.io/badge/copier-ab79d2)](https://copier.readthedocs.io/)


copier template for Python-based libraries / packages

- opinionated
- use namespace packages to avoid naming collisions
- use uv & tox for all our development needs
- use dependabot, pdm-backend, pre-commit & release-please for all our packaging needs

__namespaces__

> A namespace package in Python is a way to split a single Python package across multiple directories or locations, allowing multiple packages or modules to contribute to the same package namespace. This is useful for creating modular and extensible libraries or applications where various components can be distributed independently but still belong to the same package.
>
> Namespace packages are typically used for extensibility and modularity. They’re handy when you want to create an ecosystem of plugins or modules that can be added or removed independently.

## Usage

It is possible inject the template into an existing repository or update
a templated repository with a newer template version.

### inject the template into a repository

__Warning:__ Depending on the current configuration and repository layout
this may wreck the repository. It is recommended to initialize the
template into an empty directory. Afterwards copy the files from the
existing repository into the new location and adjust them as needed.

__option a)__ automatically run post-initialization commands

```SHELL
# 'git clone <...>' or 'mkdir <...>'
cd <repodir>

# initialize and post-init
copier copy --trust https://github.com/feeph/pypackage-template.git .

# start coding
uv run pytest
```

__option b)__ manually complete the initialization

```SHELL
# 'git clone <...>' or 'mkdir <...>'
cd <repodir>

# initialize
copier copy https://github.com/feeph/pypackage-template.git .

# post-init
pre-commit install
uv sync

# start coding
uv run pytest
```

### apply an updated template

A script was provided to help with the update process. It assumes all answer
files comply with naming scheme `.copier/answers_<templatename>.yaml`.

This allows us to compose multiple templates into a single repository.

```SHELL
# update and post-update
scripts/update_copier-templates --trust
```

or

```SHELL
# update
scripts/update_copier-templates

# post-update
pre-commit install
uv sync
```

## Bugs & Features

Please submit bugs and feature requests on the [issue tracker](https://github.com/feeph/pypackage-template/issues).

Contributions are always welcome.

## How to contribute

Please refer to the [Contribution guide](docs/CONTRIBUTING.md).
