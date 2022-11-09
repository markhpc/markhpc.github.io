# Playing with io_uring in Ceph

Recently I got a chance to review and play around with the io_uring support [added](https://github.com/ceph/ceph/pull/27392) to Ceph by Roman Penyaev.  The gist of it:  Not a big [change](https://docs.google.com/spreadsheets/d/1OVHtaCJ9ExGtHXbpIYfR3Ak-3F2IrhVMT5eqwrBPUy8/edit?usp=sharing).  We probably have too much latency in other parts of the stack for this to matter much.  Having said that, we do sometimes see blocking io_submit, so getting away from libaio is still probably a good move in the long run.
