# Python via Pyenv

## pyenv

Run:

```bash
export PYENV_GIT_TAG=v2.8.5 && curl -fsSL https://pyenv.run | bash
```

Run:

```bash
~/.pyenv/bin/pyenv init --install
```

Reload your shell or rerun your shell script.

## Python

**Dependencies:**

- pyenv

From inside the project root directory, run:

```bash
pyenv install --skip-existing "$(pyenv local)"
```
