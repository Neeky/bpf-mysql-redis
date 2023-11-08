## 概要
当一个 set 比较大时候它的底层实现是 hashtable，hashtable 的底层实现又是数组；有时候我们需要知道当前已经分配的数组长度，和当前 set 中的元素数量。

---

## 使用
```bash
bpftrace -I /data/repos/redis-7.0.11/src trace-dict-size.bt
```

---


