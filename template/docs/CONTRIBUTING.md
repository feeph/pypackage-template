# Contributing

## quickstart

### one-time setup

Install `uv`:

_follow the instructions on
https://docs.astral.sh/uv/getting-started/installation/_

Install development tools:

```SHELL
uv tool install pre-commit
uv tool install tox --with tox-uv
```

Verify installation by executing `tox --version`. The output should look like this:

```
ROOT: No tox.ini or setup.cfg or pyproject.toml or tox.toml found, assuming empty tox.ini at /home/thomas/github/pypackage-template
4.24.2 from /home/thomas/.local/share/uv/tools/tox/lib/python3.12/site-packages/tox/__init__.py
registered plugins:
    tox-uv-1.25.0 at /home/thomas/.local/share/uv/tools/tox/lib/python3.12/site-packages/tox_uv/plugin.py with uv==0.6.8
```

### repository setup

```SHELL
pre-commit install
uv sync
```

### execute code

```SHELL
uv run path/to/code.py
```

### perform unit tests:

```SHELL
uv run pytest
```

### perform compatibility tests:

```SHELL
tox
```

## Process and conventions

TODO Please describe your team-specific processes and conventions.

It is helpful to describe:

 - how to request contributor permissions
 - what needs to be done to prepare a pull request
 - which standards to follow
 - which tests must be run
 - who is going to perform the code review
