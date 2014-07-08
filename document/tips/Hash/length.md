### ハッシュの要素の数を調べる

---

Rubyでは**Hash#length**または**Hash#size**を使用することで、ハッシュの要素の数を調べることが出来ます。


サンプルコード
```ruby
hash = { a: 1, b: 2, c: 3 }

p hash.length
p hash.size
```

実行結果
```
3
3
```
