# Opinion Dynamics — Code Examples

This repository contains the material accompanying the lecture on opinion dynamics given by **Henrique F. de Arruda**, invited by **Prof. Diego R. Amancio**, as part of the discipline **SCC5882**.

## Conda environment

The project uses the Conda environment `icmc`. From the repository root, create it with:

```bash
conda env create --file environment.yml
```

Activate the environment:

```bash
conda activate icmc
```

Start JupyterLab:

```bash
jupyter lab
```

If the environment already exists and `environment.yml` changes, update it with:

```bash
conda env update --name icmc --file environment.yml --prune
```
