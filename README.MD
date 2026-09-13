# Opinion Dynamics — Code Examples

This repository contains the material accompanying the lecture on opinion dynamics given by **Henrique F. de Arruda**, invited by **Prof. Diego R. Amancio**, as part of the discipline **SCC5882**.

## Notebooks

This repository contains didactic examples of different models of opinion dynamics.

- `1_degroot.ipynb` -- DeGroot opinion averaging dynamics.
- `2_voter.ipynb` -- Voter-model opinion copying dynamics.
- `3_deffuant.ipynb` -- Deffuant bounded-confidence pairwise dynamics.
- `4_holme_newman.ipynb` -- Holme-Newman coevolution of opinions and network links.

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

## Acknowledgment

These examples were developed by the author, with partial assistance from OpenAI Codex. All code was reviewed and validated by the author.
