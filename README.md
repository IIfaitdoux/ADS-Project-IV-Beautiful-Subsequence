# Simple Introduction of the Programme

## 1.Fenwick Tree (Binary Indexed Tree)

This project uses this data_structure, which can **calculate the sum of elements of a given sequence in the given range (l,r) very quickly**. We use it to **prune**. We can simply ignore the range(a[i]-m,a[i]+m) in our algorithm.

For details of this data structure, go to [树状数组(详细分析+应用)，看不懂打死我!-CSDN博客](https://blog.csdn.net/TheWayForDream/article/details/118436732)

## 2.Algorithm Specification

### 2.1 Definition

1. int n,m: the length of input sequence and the difference which must exist in a beautiful subsequence.
2. int a[MAX_N]: the input sequence.
3. long long tree[MAX_VAL]: the Fenwick Tree sequence, the elements of which **relate to**(<font color="red">note: just relate to, not equal</font>) the number of ugly subsequences which ends with i.
