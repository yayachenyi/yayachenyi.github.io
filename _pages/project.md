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

* SQL on the fly
  * Built a lightweight and fast database system with Python that provides commercial database speed SQL querying over large size (larger than memory) CSV files.
  * Developed a memory-efficient system to handle SQL queries over raw CSV files directly.
  * Sped up the system with indexing (B-Tree and Hash), query processing and optimization techniques.
  * 50-300 times faster and much smaller memory usage than similar open source system ''q - Text as Data''

* Online Query Spelling Correction API Service
  * Implemented the API service with Python, Numpy, Flask and deployed on Azure to provide query correction service
  * Trained a generalized Hidden Markov Model (gHMM) for query spelling correction
  * Designed JSON based API with Flask to allow customized error models and N-gram models

* Smart Route Planner, hackathon project (Hackital)
  * Built an Amazon Alexa skill to generate the best route among multiple destinations based on user preferences with AWS Lambda function, node.js, Express, Python and Google cloud
  * Implemented backend with node.js to explore the best route that meets user requirements using Google Map API
  * Programmed AWS Lambda function with Python to parse user voice input and present backend calculated result
  
Reseach Projects
======
* Meta-Graph Based HIN Spectral Embedding
  * Conducted systematic empirical analysis of the effectiveness of meta-graph assessment and combination.
  * Built an AutoEncoder model with L2,1-loss for achieving meta-graph selection, combination and embedding dimension reduction simultaneously.
  * Experimented comprehensively by comparing with state of the art models on large real-world HINs.
  * Led and conducted extensive comprehensive evaluations by comparing with state of art models on large datasets.

* Condition Rating Survey Project, Illinois Center of Transportation
  * Developed pavement condition prediction model by processing, analyzing and modeling all the pavement data of Illinois to help Illinois Department of Transportation (IDOT) maintain all the pavements in Illinois.
  * Built a pipeline system for pavement CRS data processing, analyzing and modeling.
  * Increased data processing and analyzing speed 400% by reimplementing original program with better algorithms and R using dplyr and tidyr
  * Visualized the data automatically using ggplot2, grid and gridExtra to achieve intuitional representation
