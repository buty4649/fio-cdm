**Notice: This Repository is No Longer Active**

This repository is no longer active. If you're looking for a benchmarking tool compatible with Crystal Disk Mark for Linux, please consider using the following software alternatives:

1. **[JonMagon/KDiskMark](https://github.com/JonMagon/KDiskMark):** A simple open-source disk benchmark tool for Linux distributions.
2. **[microsoft/diskspd-for-linux](https://github.com/microsoft/diskspd-for-linux):** A disk I/O load-generator and benchmarking tool for Linux, inspired by the Windows tool diskspd, which is internally used by Crystal Disk Mark.
3. **[axboe/fio](https://github.com/axboe/fio):** Flexible I/O Tester, a robust and versatile tool for benchmarking and testing disk I/O.

For more information and updates, please follow the respective links to their GitHub repositories.

----

# fio-cdm
fioでCrystalDiskMarkっぽい計測を行うコマンド

## Usage

```
fio <path>
```

### sample

```
# fio-cdm /mnt/sdf1
|      | Read(MB/s)|Write(MB/s)|
|------|-----------|-----------|
|  Seq |    305.307|    138.191|
| 512K |    275.565|    139.452|
|   4K |     22.208|     37.098|
|4KQD32|    210.052|    125.907|
```

## 参考
* [LinuxのI/OベンチマークでCrystalDiskMarkと同等の計測をfioで実現 - WinKey](http://www.winkey.jp/article.php/20110310142828679)
