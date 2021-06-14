Singularity image for Eclipser (https://github.com/SoftSec-KAIST/Eclipser)

[![singularity-deploy](https://github.com/shub-fuzz/eclipser/actions/workflows/builder.yml/badge.svg?branch=main)](https://github.com/shub-fuzz/eclipser/actions/workflows/builder.yml)

- __What__ is [Singularity](https://sylabs.io/singularity/)??  
  A containerization system primarily used by the scientific community on high-performance computing (HPC).
  On many University HPC systems, docker is not allowed, but singularity is availble because it runs with 
  user level permisions.  
- __Why__?  
  Fuzzing on HPC!  
  Universities have trememdous resources available in HPC clusters that can be used to support 
  large-scale fuzzing evaluations.


- usage:

```
singularity pull --name eclipser.sif https://github.com/shub-fuzz/eclipser/releases/download/0.0.2/shub-fuzz-eclipser.1604.sif

singularity shell eclipser.sif
```
