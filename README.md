# ANN-LSH

a) LSH Random projections 

Technique that hashes similar input items into the same "buckets" with high probability. Used FAISS library.  

b) exhaustive search:

Comparing each point to every other point, which will require Linear query time (the size of the dataset).

c) product quantization:

dramatically compressing high-dimensional vectors to use 97% less memory, and for making nearest-neighbor search speeds 5.5x faster in our tests

d) trees and graphs

e) Hierarchical Navigable Small Worlds (HNSW)
