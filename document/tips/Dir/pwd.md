### カレントディレクトリを取得する

---

Rubyでは**Dir#pwd**か**Dir#getwd**を使用することで、カレントディレクトリを取得することができます。

サンプルコード
```ruby
puts Dir::pwd
```

実行結果
```
/Users/siman/Programming/ruby/test% ruby pwd.rb                                                                 [master]
/Users/siman/Programming/ruby/test
```
