# vitessce_suts

[![Tests][badge-tests]][link-tests]
[![Documentation][badge-docs]][link-docs]

[badge-tests]: https://img.shields.io/github/actions/workflow/status/your_github_username/vitessce_suts/test.yaml?branch=main
[link-tests]: https://github.com/your_github_username/vitessce_suts/actions/workflows/test.yml
[badge-docs]: https://img.shields.io/readthedocs/vitessce_suts

A very interesting piece of code

## Setting up

1. Clone the repository:

```zsh
    git clone https://github.com/karadavis-lab/suts_2024.git
```

2. Ensure you have Conda / Anaconda Installed, we recommend installing [Miniforge](https://github.com/conda-forge/miniforge). 3.`cd` into `suts_2024` and create the conda environment with

```zsh
    conda env create -f environment.yml
```

4. Activate the environment with `conda activate suts`
5. There are two notebooks which can be run in the `scripts` directory:

    1. `process_fcs.ipynb` if you would like to reproduce the data for vitessce. 2.`vitessce.ipynb` is the notebook for running the visualization.

    **Currently we recommend just running the vitessce notebook as teh data is already preprocessed for ingestion.**
