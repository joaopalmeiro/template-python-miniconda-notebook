# template-python-miniconda-notebook

[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

Opinionated [Python](https://www.python.org/) + [Miniconda](https://docs.anaconda.com/free/miniconda/) template for new notebooks.

## Development

Install [Miniconda](https://conda.io/projects/conda/en/latest/index.html) (if necessary).

```bash
conda env create -f environment.yml
```

```bash
conda env list
```

```bash
conda activate template-python-miniconda-notebook
```

```bash
conda list
```

```bash
jupyter lab
```

```bash
ruff check
```

```bash
ruff check --fix
```

```bash
ruff format
```

```bash
conda deactivate
```
