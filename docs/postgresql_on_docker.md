# PostgreSQL on Docker

## 1. PostgreSQL on Docker introduction

* Differences between running in container vs O/S.
* Best practice considerations.
* Available container images and how they differ - official vs vendor provided.
* Getting PostgreSQL on docker up and running using docker-compose.
* Persistent data and data layout options.
* Securing everything using TLS.

## 2. PostgreSQL extras

* Monitoring with Prometheus in a separate container.
* Log collection using Filebeat in a separate container.
* How to perform backups, what are the options.
* Other supporting containers: pgadmin, pgbadger.
* Putting it all together with docker-compose.

## 3. Performance and monitoring

* Using pgbench to generate different workloads.
* Seeing what metrics are affected and what it means.
* How does high write load affect checkpoints and WAL generation.
* What happens when there is to much load.
* What configuration options can affect the behaviour.
* How to generate a baseline to provide throughput and latency measures.

## 4. Replication

* Options for replication.
* Typical Master / Slave setup with containers.
* Performing failovers.
* Measuring the impact when generating high load.
* Configuration options, what they do and how do they influence performance.
* Recovering from a failure.
