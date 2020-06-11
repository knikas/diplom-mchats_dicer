This code is part of DICER: Diligent Cache Partitioning for Efficient Workload Co-location publication. Link below:

https://dl.acm.org/citation.cfm?id=3337891

Use config-core.cfg for core monitoring or config-os.cfg for PID monitoring
Make sure to specify correct paths in run_executables.sh

Added options in config files:
- benchmarks: hp_benchmark be_benchmark  #Choose which HP and BE benchmarks will be executed from run_executables.sh
- core-list: x x x x x x x x x x  #Set affinity for each of the 10 processes respectively by replacing x
