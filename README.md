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
- [interoparability-tutorial.ipynb](interoparability-tutorial.ipynb): showcases how full-rankers and re-rankers submitted in TIRA can be combined in new ways in post-hoc experiments.

## Up-To-Date Leaderboards

Comparing the leaderboards accross different tasks is quite interesting (we have a large scale evaluation on that in the paper), e.g., compare [MS MARCO DL 2019](https://www.tira.io/task/ir-benchmarks#msmarco-passage-trec-dl-2019-judged-20230107-training) with [Antique](https://www.tira.io/task/ir-benchmarks#antique-test-20230107-training) or [Args.me](https://www.tira.io/task/ir-benchmarks#argsme-touche-2020-task-1-20230209-training): On MS MARCO, all kinds of deep learning models are at the top, which totally reverses for other corpora, e.g., Args.me or Antique.


The current leaderboards can be viewed in [tira.io](https://www.tira.io/task/ir-benchmarks):

- [Antique](https://www.tira.io/task/ir-benchmarks#antique-test-20230107-training)
- [Args.me 2020 Task 1](https://www.tira.io/task/ir-benchmarks#argsme-touche-2020-task-1-20230209-training)
- [Args.me 2021 Task 1](https://www.tira.io/task/ir-benchmarks#argsme-touche-2021-task-1-20230209-training)
- [Cranfield](https://www.tira.io/task/ir-benchmarks#cranfield-20230107-training)
- [TREC COVID](https://www.tira.io/task/ir-benchmarks#cord19-fulltext-trec-covid-20230107-training)
- [TREC Deep Learning 2019 (passage)](https://www.tira.io/task/ir-benchmarks#msmarco-passage-trec-dl-2019-judged-20230107-training)
- [TREC Deep Learning 2020 (passage)](https://www.tira.io/task/ir-benchmarks#msmarco-passage-trec-dl-2020-judged-20230107-training)
- [TREC Genomics 2004](https://www.tira.io/task/ir-benchmarks#medline-2004-trec-genomics-2004-20230107-training)
- [TREC Genomics 2005](https://www.tira.io/task/ir-benchmarks#medline-2004-trec-genomics-2005-20230107-training)
- [TREC 7](https://www.tira.io/task/ir-benchmarks#disks45-nocr-trec7-20230209-training)
- [TREC 8](https://www.tira.io/task/ir-benchmarks#disks45-nocr-trec8-20230209-training)
- [Robust04](https://www.tira.io/task/ir-benchmarks#disks45-nocr-trec-robust-2004-20230209-training)
- [TREC Web Track 2002 (gov)](https://www.tira.io/task/ir-benchmarks#gov-trec-web-2002-20230209-training)
- [TREC Web Track 2003 (gov)](https://www.tira.io/task/ir-benchmarks#gov-trec-web-2003-20230209-training)
- [TREC Web Track 2004 (gov)](https://www.tira.io/task/ir-benchmarks#gov-trec-web-2004-20230209-training)
- [TREC Web Track 2009 (ClueWeb09)](https://www.tira.io/task/ir-benchmarks#clueweb09-en-trec-web-2009-20230107-training)
- [TREC Web Track 2010 (ClueWeb09)](https://www.tira.io/task/ir-benchmarks#clueweb09-en-trec-web-2010-20230107-training)
- [TREC Web Track 2011 (ClueWeb09)](https://www.tira.io/task/ir-benchmarks#clueweb09-en-trec-web-2011-20230107-training)
- [TREC Web Track 2012 (ClueWeb09)](https://www.tira.io/task/ir-benchmarks#clueweb09-en-trec-web-2012-20230107-training)
- [TREC Terabyte 2004 (gov2)](https://www.tira.io/task/ir-benchmarks#gov2-trec-tb-2004-20230209-training)
- [TREC Terabyte 2005 (gov2)](https://www.tira.io/task/ir-benchmarks#gov2-trec-tb-2005-20230209-training)
- [TREC Terabyte 2006 (gov2)](https://www.tira.io/task/ir-benchmarks#gov2-trec-tb-2006-20230209-training)
- [NFCorpus](https://www.tira.io/task/ir-benchmarks#nfcorpus-test-20230107-training)
- [Vaswani](https://www.tira.io/task/ir-benchmarks#vaswani-20230107-training)
- [TREC Core 2018 (wapo)](https://www.tira.io/task/ir-benchmarks#wapo-v2-trec-core-2018-20230107-training)
- [TREC Precision Medicine 2017](https://www.tira.io/task/ir-benchmarks#medline-2017-trec-pm-2017-20230211-training)
- [TREC Precision Medicine 2018](https://www.tira.io/task/ir-benchmarks#medline-2017-trec-pm-2018-20230211-training)
