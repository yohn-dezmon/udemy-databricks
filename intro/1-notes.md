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

Azure:

- https://portal.azure.com/#home
- Azure Databricks
- Create
- Create new resource group
- ah, my Azure account (for dbs) has already expired (it was only 14 days)

Databricks/Azure workspace UI:

- you can link a github repository with the Repos tab within the workspace!
- github repo: https://github.com/derar-alhussein/Databricks-Certified-Data-Engineer-Associate
- you can create notebooks
- you can create clusters
- you can manage experiments
- you can create a feature store

Creating a cluster:

- Compute > New > Autoscaling settings, runtime version, terminate after x mins of inactivity
- Master node == driver
- worker nodes

DBUs:

- databricks units
- unit of processing capability per hour
- it is reflective of how many nodes are in your cluster, though it is not 1:1

Cluster interface:

- Compute
- Driver Logs --> shows logs from notebooks etc.
- Event Log --> shows which nodes are healthy/unhealthy
