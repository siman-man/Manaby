### ハッシュの中身を空にする

---

Rubyでは**Hash#clear**を使うことでハッシュの中身を空にすることができます。


サンプルコード
```ruby
hash = { a: 1, b: 2, c: 3 }

p hash

hash.clear

p hash
```

実行結果
```
{:a=>1, :b=>2, :c=>3}
{}
```
