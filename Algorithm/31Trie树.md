在搜索引擎搜索关键字弹出提示框，其实这些关键字是预先放在Trie树这个数据结构中的。

在一组字符串中查找某个或某几个字符串，通常可以通过散列表、红黑四、字符串匹配的各种算法中实现，但Trie树有其独有优势。

Trie树利用字符串之间的公共前缀，将重复的前缀合并在一起。