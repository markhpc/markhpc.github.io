# Cache Age Binning PR Finally Merged!

I've had this PR hanging around in various forms for years.  It's basically the last peice of the OSD memory target code.  We can now get a "binned" view of the relative ages of items in different LRU caches and dynamically adjust target sizes for different caches.  PR is [here](https://github.com/ceph/ceph/pull/43299) and memory usage behavior charts are [here](https://docs.google.com/spreadsheets/d/1lSp2cLzYmRfPILDCyLMXciIfdf0OvSFngwXukQFXIqQ/edit?usp=sharing).
