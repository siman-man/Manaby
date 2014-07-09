### 要素が含まれているかどうかを調べる

---

Rubyでは**Array#include**を使うことで、配列の中に指定した要素が含まれているかどうかを調べることができます。

サンプルコード
```ruby
array = [1,2,3,4,5]

p array.include?(3)
p array.include?(10)
```

実行結果
```
true
false
```
