# Python via Pyenv

## pyenv

Run:

```bash
apt install make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev curl git libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev libzstd-dev
```

Run:

```bash
export PYENV_GIT_TAG=v{{VERSION}} && curl -fsSL https://pyenv.run | bash
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
