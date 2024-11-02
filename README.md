# LDBC
Linked Data Benchmark Council (LDBC) is a non-profit organization aiming to define standard graph benchmarks to foster a community around graph processing technologies. 

LDBC defines standard graph benchmarks to accelerate progress in graph data management similarly to what TPC has been doing in the relational data management space. LDBC is also active in promoting standard graph query languages such as SQL and SQL/PGQ. For a brief introduction, see the presentation on LDBC and the accompanying [paper](http://ldbcouncil.org/docs/papers/ldbc-organization-tpctc2023-preprint.pdf).

# LDBC Benchmarks
LDBC currently offers the following benchmarks:
  - [Graphalytics](http://ldbcouncil.org/benchmarks/graphalytics/): Graph algorithms for graph analytical platforms
  - [Financial](http://ldbcouncil.org/benchmarks/finbench/) Benchmark: Benchmark for financial workloads, targeting distributed systems
  - [Semantic Publishing Benchmark](http://ldbcouncil.org/benchmarks/spb/): An RDF-based benchmark for semantic databases
  - [Social Network Benchmark Suite](http://ldbcouncil.org/benchmarks/snb/) (SNB): The SNB targets database management systems with graph-processing capabilities. It consists of two workloads, Interactive and Business Intelligence

# Social Network Benchmark (SNB)
This repository is supporting the LDBC Social Network Benchmark for TigerGraph. To run this benchmark will require you to install User Defined Functions (UDF) for two of the queires (interactiveInsert1.gsql & interactiveComplex14.gsql)[^1].

The Social Network Benchmark’s [specification](https://arxiv.org/pdf/2001.02299) can be found on arXiv.

[^1]: See supporting function files under LDBC/UDF directory.
