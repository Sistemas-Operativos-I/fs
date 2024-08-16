### Sistemas Operativos I - FCEFyN - UNC


#### Analyzing and Optimizing File System Performance

## Objective:
Investigate the performance characteristics of different file systems on Linux, such as ext4, XFS, and Btrfs, under various workloads. Optimize a given file system configuration for a specific workload to improve performance.

## Task Description:


### Set Up the Environment:

Install and configure multiple Linux file systems (e.g., ext4, XFS, Btrfs) on separate partitions or virtual machines.
Ensure you have a benchmarking tool available, such as [fio](https://github.com/axboe/fio) or [bonnie++](https://doc.coker.com.au/projects/bonnie/).


### Design Benchmark Tests:

Define a set of workloads to simulate typical use cases, such as large file reads/writes, small file operations, and mixed I/O patterns.
Include tests for sequential and random access patterns.


### Conduct Benchmarks:

Perform benchmark tests on each file system using the defined workloads.
Collect data on various performance metrics, such as throughput, latency, and CPU usage.

### Analyze Results:

Compare the performance of different file systems under each workload.
Identify strengths and weaknesses of each file system in handling different types of operations.


### Optimize File System Configuration:

Select one file system and a specific workload.
Experiment with different configuration options and parameters to optimize performance (e.g., block size, journaling settings).
Validate improvements through additional benchmarking.


### Document Findings:

Write a report detailing the benchmarking process, results, and analysis.
Include insights on the best file system choice for different workloads and the effect of optimizations.


## Deliverables:

Benchmark scripts and raw data collected from tests.
Configuration files and settings used for optimization.
Comprehensive report with analysis and recommendations.


## Evaluation Criteria:

Completeness and accuracy of benchmarking and analysis.
Depth of optimization efforts and improvements achieved.
Clarity and thoroughness of documentation and report.
Insightfulness of recommendations and conclusions.

## Readings

- [System Profiling and Tuning](https://github.com/poornalingam/PerformanceEngineeringService/blob/master/system-profiling-and-tuning/filesystem-profiling.md)
- [Chapter 7. File Systems](https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/6/html/performance_tuning_guide/main-fs)
