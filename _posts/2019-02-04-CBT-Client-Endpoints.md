# CBT Client Endpoints Testing

Recently I added support in [CBT](https://github.com/ceph/cbt) to abstract benchmarking code from rbd, cephfs, etc so that we could run the exact same benchmarks against different endpoint types.

This [shreadsheet](https://docs.google.com/spreadsheets/d/1oJZ036QDbJQgv2gXts1oKKhMOKXrOI2XLTkvlsl9bUs/edit?usp=sharing) showcases how we can now run the exact same fio benchmark configuration against rbd-kernel, librbd, rbd-nbd, rbd-tcmu, rbd-fuse, cephfs-kernel, and cephfs-fuse!
