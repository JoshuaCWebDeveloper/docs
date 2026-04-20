# Autoenv

Installing autoenv eliminates the need to run {{ List all environment switching commands for project (i.e. `nvm use`, `conda activate projectname`, etc.) }} every time you `cd`
into the project.

**Dependencies:**

- {{ List all environment switching binaries for project (i.e. `nvm`, `conda`, etc.) }}

Run:

```bash
nvm use node
```

```bash
curl -#fLo- 'https://raw.githubusercontent.com/hyperupcall/autoenv/master/scripts/install.sh' | sh
```

The above command will append a line to your `~/.bashrc` file that sources
`autoenv/activate.sh`. Add the following variables to your `~/.bashrc` file
immediately _before_ the source line:

```bash
AUTOENV_ENABLE_LEAVE=yes
AUTOENV_ENV_FILENAME=.autoenv
AUTOENV_ENV_LEAVE_FILENAME=.autoenv.leave
```
