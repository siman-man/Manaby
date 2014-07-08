### 配列の要素を削除する

---

Rubyでは**Array#delete**を使用することで配列の要素を削除することができます。deleteは破壊的なメソッドです。

サンプルコード
```ruby
array = [ 1, 2, 3, 4, 5 ]

array.delete(3)

p array
```

実行結果
```
[1, 2, 4, 5]
```

また、deleteメソッドは削除する要素が存在しない場合にnilを返しますが、deleteにブロックを渡すことで、そのブロック文で評価された値を返すことができるようになります。


サンプルコード
```ruby
array = [ 1, 2, 3, 4, 5 ]

p array.delete(10)
p array.delete(10){ "Not Found" }
```

実行結果
```
nil
"Not Found"
```
