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
