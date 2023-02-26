# Shared Task on ir-benchmarks

This repository exemplifies how archived shared task repositories of the IR Experiment Platform look like.
Here, we have archived the [Retrieval Benchmarks in the IR Experiment Platform](https://www.tira.io/task/ir-benchmarks).

The archived shared task repositories allow post-hoc experiments, and we provide several tutorials with examples in Jupyter Notebooks.

To start the jupyter notebook, please clone the archived shared task repository:

```
git clone git@github.com:tira-io/ir-experiment-platform-benchmarks.git
```

Inside the cloned repository, you can start the Jupyter notebook which automatically installs a minimal virtual environment using:
```
make jupyterlab
```


The installation of the environment is simplified with a virtual environment and executing `make jupyterlab` installs the virtual environment (if not already done) and starts the jupyter notebook ready to run all parts of the tutorial.

For each of the softwares submitted to TIRA, the `tira` integration to PyTerrier loads the Docker Image submitted to TIRA to execute it in PyTerrier pipelines (i.e., a first execution could take sligthly longer).

The following tutorial notebooks are available:

- [Tutorial.ipynb](Tutorial.ipynb): A general purpose tutorial showing the first steps.
- [full-rank-retriever-tutorial.ipynb](full-rank-retriever-tutorial.ipynb): showcases how full-rankers can be reproduced/replicated.
- [re-rank-tutorial.ipynb](re-rank-tutorial.ipynb): showcases how re-rankers can be reproduced/replicated.
- [interoparability-tutorial](interoparability-tutorial): showcases how full-rankers and re-rankers submitted in TIRA can be combined in new ways in post-hoc experiments.
