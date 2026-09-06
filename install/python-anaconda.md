# Python via Anaconda

## Anaconda

Run:

```bash
curl https://repo.anaconda.com/archive/Anaconda3-{{VERSION}}-Linux-x86_64.sh -o /tmp/anaconda.sh && bash /tmp/anaconda.sh
```

Run:

```bash
conda config --set auto_activate_base false
```

## Python

**Dependencies:**

- Anaconda

From inside the project root directory, run:

```bash
conda env create
```
