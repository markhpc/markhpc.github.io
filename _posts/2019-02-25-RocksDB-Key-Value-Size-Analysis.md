# Ceph RBD RocksDB Key/Value size analysis

This [spreadsheet](https://docs.google.com/spreadsheets/d/1fNFI8U-JRkU5uaRJzgg5rNxqhgRJFlDB4TsTAVsuYkk/edit?usp=sharing) shows an analysis of RocksDB Key Value sizes in SST files after a set amount of 4KB random writes to a Ceph OSD.  This testing was done to understand if the Toshiba [trocksdb](https://github.com/KioxiaAmerica/trocksdb) modificaitons to RocksDB might help improve Ceph performance.
