---
layout: post
title: Papers on Database Management Systems
date: 2025-05-08 20:00:00
description:
tags: growth
categories: sample-posts
giscus_comments: true
related_posts: false
related_publications: true
---

This post summarizes the key dependencies and evolution among several influential distributed systems(GFS, MapReduce, DryadLINQ, CIEL, and Spark RDD) papers.
See assets/papers_to_read/.

---

### 1. **The Google File System (GFS, 2003)**

- **Role**: Foundational distributed storage layer that powered MapReduce.
- **Dependency**: None.
- **Influenced**: MapReduce, Hadoop DFS, Spark's support for HDFS.

---

### 2. **MapReduce: Simplified Data Processing on Large Clusters (2004)**

- **Depends on**: GFS (for reading/writing input and output data).
- **Influenced**:
  - Hadoop MapReduce
  - Spark RDD (as a reaction and evolution)
  - DryadLINQ and CIEL (as generalizations of the dataflow idea)

---

### 3. **DryadLINQ (2008)**

- **Depends on**:
  - MapReduce (as inspiration)
  - LINQ query expression model
- **Adds**: DAG-based dataflows and general-purpose parallelism beyond map/reduce.
- **Influenced**: CIEL and partially Spark's DAG Scheduler

---

### 4. **CIEL (2011)**

- **Depends on**:
  - Dryad's dataflow DAG model
- **Adds**:
  - Dynamic task generation (tasks can spawn new tasks at runtime)
- **Influenced**: Dynamic execution models in later systems, including Spark's adaptive planning.

---

### 5. **Resilient Distributed Datasets (Spark RDD, 2012)**

- **Depends on**:
  - MapReduce's fault tolerance model
- **Adds**:
  - Lineage-based fault recovery
  - In-memory computation and coarse-grained transformations
- **Influenced**: Spark's evolution (DataFrames, Datasets) and lineage-aware systems like Flink.

---

### Summary Dependency Graph

```
GFS (2003)
  ↓
MapReduce (2004)
  ↓               ↘
DryadLINQ (2008)  → Spark RDD (2012)
      ↓                  ↑
     CIEL (2011) --------┘
```
