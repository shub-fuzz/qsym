Singularity Image for QSYM (https://github.com/sslab-gatech/qsym)

[![singularity-deploy](https://github.com/shub-fuzz/qsym/actions/workflows/builder.yml/badge.svg?branch=main)](https://github.com/shub-fuzz/qsym/actions/workflows/builder.yml)
[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/3625)

- __What__ is [Singularity](https://sylabs.io/singularity/)?  
  A containerization system primarily used by the scientific community on high-performance computing (HPC).
  On many University HPC systems, docker is not allowed, but singularity is availble because it runs with 
  user level permisions.  
- __Why__?  
  Fuzzing on HPC!  
  Universities have trememdous resources available in HPC clusters that can be used to support 
  large-scale fuzzing evaluations.


QSYM  - Concolic Execution Engine (https://github.com/sslab-gatech/qsym)

- usage:

```
singularity pull --name qsym.sif https://github.com/shub-fuzz/qsym/releases/download/0.0.2/shub-fuzz-qsym.1604.sif

singularity shell qsym.sif
```

