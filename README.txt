
DIRNT is a hybrid non-termination checker that (1) uses bounded symbolic
reasoning to generate concrete values for nondeterministic assignments to
variables that can steer program execution towards states that recur, (2)
substitutes these values into the program, and (3) executes the program to
check for recurrence. What makes DIRNT unique as well as efficient is its
systematic search for recurrence seeking tests that guide the symbolic
reasoning engine.

The zip file dirnt.zip unzips into another folder named "dirnt", which is self-contained. The README there of gives the complete details of the archive, including how to run the tool. This archive also has scripts and instrumented benchmakrs for you to run DIRNT on all SV-COMP 2025 non-termination benchmarks and all OOS benchmarks, by just invoking the scripts.
