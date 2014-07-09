### 全ての要素が0かどうかを調べる

---

**Enumerable#all?**と**Integer#zero?**を組み合わせることで、配列の要素全てが0かどうかを調べることができます。

サンプルコード
```ruby
array = [ 1, 2, 3, 4, 5 ]
zeros = [ 0, 0, 0, 0, 0 ]

p array.all?(&:zero?)
p zeros.all?(&:zero?)
```

実行結果
```
false
true
```
