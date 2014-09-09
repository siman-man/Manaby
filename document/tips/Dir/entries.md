### カレントディレクトリを取得する

---

Rubyでは**Dir#entries**を使用することで、指定したpathのファイル/ディレクトリ一覧を取得することができます。

サンプルコード
```ruby
p Dir::entries('.')
```

実行結果
```
/Users/siman/Programming/ruby/test/temp% ruby entries.rb                                                        [master]
[".", "..", "entries.rb"]
```
