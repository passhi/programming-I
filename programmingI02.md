# プログラミングI　第2回　授業資料

## 第２回：プログラムの実行方法とRuby言語の文法の基本

### paiza.io を利用する

[https://paiza.io/ja](https://paiza.io/ja)

Ruby言語を選択して、paiza.io をブラウザにブックマークする


### プログラムを書いて実行してみる

エディター領域に以下のプログラムをコピーしてペーストする

```
print("hello world")
```

* 実行ボタンをクリックして実行
* 実行結果領域で結果を確認する
* hello world と表示されれば成功

### print文なしで文字列を実行すると

```
"hello world"
```

* 実行ボタンをクリックして実行
* 実行結果領域には何も表示されない

### printメソッドは改行しない

```
print("ジョーズ")
print("紅の豚")
print("サマーウォーズ")
```

### putsメソッドは改行してくれる

```
puts("ジョーズ")
puts("紅の豚")
puts("サマーウォーズ")
```

### 数値の計算(整数 Integer）

```
puts(1+2)
puts(3-4)
puts(3*5)
puts(10/3)
puts(10%3)
```

### 数値の計算(浮動小数点数 Float）

```
puts(1.0+2.0)
puts(3.0-4.0)
puts(3.0*5.0)
puts(10.0/3.0)
puts(10.0%3.0)
```

### 関係演算子の例（等号）

```
puts(2==1+1)
puts(3==1+1)
puts(2!=1+1)
puts(3!=1+1)
```

### 関係演算子の例（不等号）

```
puts(2>1+1)
puts(2>=1+1)
puts(2<1+1)
puts(2<=1+1)
```

### 論理演算子の例

```
puts(true && false)
puts(true || false)
puts(2==1+1 && 3==1+1)
puts(2==1+1 || 3==1+1)
```

### メソッドの引数のカッコは省略可能

```
puts 3+4
puts "こんにちは"
```
