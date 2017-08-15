# usbtick
background?
to know the performance of CPU, some benchmark are designed to test the performance score;

perpose?
this software is designed to capture the CPU context when runing the benchmark, so we can use this cpucontext to test the new generation CPU design;

what is CPU context?
we all know the cpu run step by step by the guide of the register CS:IP, some general register like AX, some modole-specific register(MSR), Memory Type Range Register(MTRR) and so on. With this context, CPU know where to get the following code, where to get the data and which rule she should keep.

modules,
a host machine, linux os(scientific linux), CPU simulator(software designed to bahave like CPU).
a target machine, os depend on the benchmark ENV(ubuntu or windows), driver(to get the CPU context, we must run on kernel mode), and setup GUI.
