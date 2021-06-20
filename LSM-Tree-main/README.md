# LSM-Tree
A simplified Golang implementation for log structured merge tree. `Put` and `Get` are supported. Compaction is also supported. Data is only stored in memory. Disk files are simulated by in-memory byte arrays. See https://eileen-code4fun.medium.com/log-structured-merge-tree-lsm-tree-implementations-a-demo-and-leveldb-d5e028257330 for a more elaborate documentation and how this compares to LevelDB.