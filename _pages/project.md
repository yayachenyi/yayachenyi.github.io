---
layout: archive
title: "Projects"
permalink: /project/
author_profile: true
redirect_from:
  - /project
---

{% include base_path %}


* Fault-Tolerant Distributed Graph Processing System
  * Designed and implemented Pregel-like distributed graph processing engine with C++, g++, Protobuf, Googletest and deployed on 10 Linux virtual machines
  * Developed a generic graph processing engine that supports API for Gather-Apply-Scatter model and accepts user-defined applications such as PageRank and Shortest Path.
  * Designed and implemented a Cassandra-like distributed file system for file replication with quorum write/read.
  * Built virtual ring-style failure detector to detect machine failure using Protobuf and UDP protocol with small bandwidth.
