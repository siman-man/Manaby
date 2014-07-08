### 文字列を空にする

Rubyでは**String#clear**を使うことで文字列を空にすることが出来ます。clearは破壊的なメソッドです。


サンプルコード
```ruby
word = "Hello Ruby"
p word

word.clear
p word
```

実行結果
```
"Hello Ruby"
""
```
