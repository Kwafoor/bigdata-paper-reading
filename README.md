# bigdata-paper-reading

## Classic System Design

- [The Google File System](papers/gfs.pdf) (2003) and [Bigtable: A Distributed Storage System for Structured Data](papers/bigtable.pdf) (2006): Two core components of Google's data infrastructure. GFS is an append-only distributed file system for large sequential reads (data-intensive applications). BigTable is high-performance distributed data store that builds on GFS. One way to think about it is that GFS is optimized for high throughput, and BigTable explains how to build a low-latency data store on top of GFS. Some of these might have been replaced by newer proprietary technologies internal to Google, but the ideas stand.
