# Contributing

## quickstart

### one-time setup

Install `uv`:

_follow the instructions on
https://docs.astral.sh/uv/getting-started/installation/_

Install development tools:

```SHELL
uv tool install copier
uv tool install pre-commit
```

### repository setup

```SHELL
pre-commit install
```

### test template changes

prepare data file `~/test-defaults.yaml`:

```
---
#
# copier default answer file
#
author_name: <your name>
author_email: <your email>

repository_owner: <github username or organization>
package_name: mypackage
package_namespace: mynamespace
package_description: my wonderful description
```

initialize a template

```SHELL
copier copy --defaults --trust --no-cleanup --data-file=~/test-defaults.yaml --vcs-ref=HEAD . /tmp/test-template_`date +%s`
```

## Process and conventions

TODO Please describe your team-specific processes and conventions.

It is helpful to describe:

 - how to request contributor permissions
 - what needs to be done to prepare a pull request
 - which standards to follow
 - which tests must be run
 - who is going to perform the code review
