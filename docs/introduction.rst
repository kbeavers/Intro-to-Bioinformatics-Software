Overview and learning objectives
=================================

The goal of this material is to show how bioinformatics workloads behave on an
HPC cluster (CPU threads, memory bandwidth, filesystem I/O, dependency
management, and reproducibility) and how to run representative tools
efficiently on many-core nodes.

Audience
--------

* **HPC admins** who operate many-core partitions.
* Staff who need to support users running genomics, RNA-seq, or R-based
  analyses and want hands-on familiarity with the tools and typical resource
  profiles.

Learning objectives
-------------------

By the end of this material, participants should be able to:

* Identify whether a bioinformatics tool is **CPU-bound**, **memory-bound**, or **I/O-bound**.
* Correctly request resources and set thread counts for multi-threaded tools.
* Use **Biocontainers/Singularity/Apptainer** to run common genomics and RNA-seq tools reproducibly.
* Be familiar with frequently used bioinformatics tools and how to run them.

Assumptions / prerequisites
---------------------------

* SLURM is used as the scheduler (all examples assume SLURM).
* Participants have access to a HPC cluster with many-core nodes.
* Biocontainers (or a local container registry) are available.
* Participants are comfortable with basic shell usage.