### 各桁の和を計算する

---

与えられた数の各桁の和を計算するプログラムです。サンプルでは様々なパターンでメソッドを定義しています。


サンプルコード
```ruby
class Integer
  def sum_of_digits
    to_s.chars.map(&:to_i).inject(:+)
  end
end

class String
  def sum_of_digits
    chars.map(&:to_i).inject(:+)
  end
end

def sum_of_digits(number)
  number.to_s.chars.map(&:to_i).inject(:+)
end

p sum_of_digits(123456789)
p "123456789".sum_of_digits
p 123456789.sum_of_digits
```

実行結果
```
45
45
45
```
