# Shared Task on ir-benchmarks

This repository serves as the main entrypoint to the shared task on ir-benchmarks.
The `tira` command shipped with this repository serves as entrypoint to all functionality and is used by the TIRA frontend as well.

As this repository contains a huge number of~2000 software executions (we executed some runs multiple times to double-check reproducibility), we excluded the runs from the repository as the repository would otherwise be roughly 4 GB in size. (via docker ignore, we have a complete backup outside of TIRA, please note that public runs can still be accessed via TIRA, the notebooks provide examples.)

## Evaluate Runs

You can evaluate runs with the following command:

```
./tira run-evaluate --task_id clickbait-spoiling --vm_id princess-knight --run_id 2022-07-20-12-54-28 --dataset_id clickbait-spoiling-task-01-validation-dataset-2022-08-01 --transaction_id XXXX
```

## Execute Software Submissions

TBD.

