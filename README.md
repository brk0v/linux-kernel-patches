# Linux Kernel Patches 

## PageCache statistics

page-cache-cgroup-stats-linux-3.10.patch

Provide statistics:
  * general_read – total syscalls: pread, read, readv, sendfile;
  * submit_bio_read – total io read on block level.

Path: 
```
/sys/fs/cgroup/memory/pagecache_stat
```
