IMPORTANT:

The artifact evaluated for the paper is available on Zenodo:

https://zenodo.org/records/19165231

The Zenodo archive is the authoritative version used for artifact
evaluation and contains the exact contents referenced in the paper.
This repository may contain development versions.
For artifact evaluation and reproducibility, please use the Zenodo archive.


DIRNT is a hybrid non-termination checker that (1) uses bounded symbolic
reasoning to generate concrete values for nondeterministic assignments to
variables that can steer program execution towards states that recur, (2)
substitutes these values into the program, and (3) executes the program to
check for recurrence. What makes DIRNT unique, as well as efficient, is its
systematic search for recurrence-seeking tests that guide the symbolic
reasoning engine.


The archive dirnt.zip extracts into a directory named "dirnt", which is
self-contained. The README within that directory provides complete details
about the artifact, including setup instructions and how to run the tool.

The archive includes scripts and instrumented benchmarks that allow running
DIRNT on all SV-COMP 2025 non-termination benchmarks and on all OSS
benchmarks by directly invoking the provided scripts.
