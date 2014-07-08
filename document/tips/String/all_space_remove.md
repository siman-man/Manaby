### 文字列中の空白を全て削除する

---

文字列中の空白を全て削除したい場合には**String#gsub**を使用して空白を全て空文字に置き換えればいいです。

サンプルコード
```ruby
p " ".gsub(/\p{blank}/,'')
p " 　".gsub(/\p{blank}/,'')
p "Hello Ruby".gsub(/\p{blank}/,'')
p "He lo R by".gsub(/\p{blank}/,'')
p "山田　太郎".gsub(/\p{blank}/,'')
```

実行結果
```
""
""
"HelloRuby"
"HeloRby"
"山田太郎"
```

---

#### 参考サイト

* [Ruby 2.1.0 リファレンスマニュアル > 正規表現](http://docs.ruby-lang.org/ja/2.1.0/doc/spec=2fregexp.html)
