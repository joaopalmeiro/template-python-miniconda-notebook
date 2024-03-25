# template-python-miniconda-notebook

[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

Opinionated [Python](https://www.python.org/) + [Miniconda](https://docs.anaconda.com/free/miniconda/) template for new notebooks.

## Getting Started

1. Go to or create the project folder.
2. Get the template files:

```bash
npx degit github:joaopalmeiro/template-python-miniconda-notebook
```

or

```bash
npx degit github:joaopalmeiro/template-python-miniconda-notebook --force
```

3. Search for `template-python-miniconda-notebook` and replace it with the project name. Ignore the template repository URL in the [NOTES.md](NOTES.md) file.
4. Search for `Opinionated [Python](https://www.python.org/) + [Miniconda](https://docs.anaconda.com/free/miniconda/) template for new notebooks.` and replace it with the (short) project description.
5. Search for `João Palmeiro` and replace it with the author's name.
6. Open the [environment.yml](environment.yml) file and add the project-specific dependencies.
7. Delete the [TEMPLATE.md](TEMPLATE.md) file.
8. Delete the [`Getting Started`](#getting-started) section.

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
