# Single-cell RNA sequence QA

A pipeline to independently verify scRNA-seq metadata by extracting signal directly from raw sequence reads - without data download or full realignment. Current plans include:

* cell vs nucleus suspension
* 3' vs 5' end bias
* donor sex
* 10X kit
* cell barcodes in reads vs those in a matrix

Built using Claude Code

Development: run `pre-commit install` once to lint on commit; CI enforces the same via `ruff check .` and `ruff format --check .`.

Status: planning
