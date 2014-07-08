### ハッシュが空かどうかを調べる

---

Rubyでは**Hash#empty**を使うことでハッシュが空かどうかを調べることが出来ます。


サンプルコード
```ruby
hoge = {}
piyo = { a: 1, b: 2, c: 3 }

p hoge.empty?
p piyo.empty?
```

実行結果
```
true
false
```
