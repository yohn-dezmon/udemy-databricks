# Introduction

Control Plane:
- web UI
- Cluster management
- Workflows
- Notebooks

Data Plane:
- customer cloud account
- cluster VMs
- Storage (DBFS)

Spark:
- databricks developed by the engineers who created spark
- in-memory, distributed data processing
- batch & stream processing

native support for DBFS:
- distributed file system
- databricks file system
- clusters come preinstalled with DBFS
- abstraction layer
    - data persisted to the underlaying cloud storage
- DBFS lives within the cluster 
- data is persisted to cloud storage
- after a given cluster is terminated, the data is still stored in S3



