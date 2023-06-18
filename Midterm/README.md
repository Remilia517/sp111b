## Ruby
```

```
### 設計理念
Ruby是一種動態、開源的物件導向程式語言，它在設計上注重程式碼的可讀性和簡潔性。
Ruby的理念是減少編程時不必要的瑣碎時間以及人性化的介面設計，令編寫程式的人能感到高興。

```
puts "Hello, World!"
```
### Ruby的靈活性

Ruby同時也是相當自由的一款語言，你可以在程式中修改先前定義過的類別，也可以在某個類別的實例中定義該實例特有的方法。

```
class MyClass
  def the_method
    "general method"
  end
end

mc = MyClass.new
def mc.the_method
  "special for this instance."
end

mc.the_method
```

另外，在Ruby當中，所有的東西都是物件，甚至連基礎類別和整數都是物件

```
5.times { print "We *love* Ruby -- it's outrageous!" }
```

```
# 定義一個動物類別
class Animal
  def initialize(name)
    @name = name
  end
  
  def speak
    puts "我是#{@name}，我會叫！"
  end
end

# 創建一個狗物件並呼叫方法
dog = Animal.new("小狗")
dog.speak

```
以上這些例子展示了Ruby的一些特色，如簡潔的語法、動態的物件導向、人性化的介面等。
這些特點使得Ruby成為一個極具表達力和靈活性的程式語言。

### 參考資料
部分程式碼來自CHATGPT
https://www.ruby-lang.org/
https://zh.wikipedia.org/zh-tw/Ruby
