# 指令

在程式語言中，指令是讓電腦執行特定動作的命令。指令可以用來控制程式的流程，例如判斷條件、迴圈、變數賦值等等。在 Swift 語言中，指令是構成程式的最基本單位，也是程式執行的起點。

## 範例：製作三明治

讓我們先來看一個生活中的例子。假設你要做一個簡單的三明治，你需要進行一系列指令。首先是取出兩片麵包，再將麵包上抹上一些醬料。接下來，加入想要的食材，例如火腿、起司和生菜。最後，將兩片麵包組合起來，一個簡單的三明治就完成了。

```swift
takeBread() // 取出兩片麵包
addSauce() // 將醬料抹在麵包上
addIngredients() // 加入想要的食材
combineBread() // 將兩片麵包組合起來
```

```mermaid
graph LR;
    A[取出兩片麵包] --> B[將醬料抹在麵包上];
    B --> C[加入想要的食材];
    C --> D[將兩片麵包組合起來];
```

## 後記

除了簡單的輸出指令，Swift 語言還提供了許多不同的指令，例如判斷式、迴圈、函數等等。這些指令可以幫助我們實現更複雜的功能。讓我們來看一個簡單的判斷式：

```swift
let age = 18
if age >= 18 {
    print("你已經成年了")
} else {
    print("你還未成年")
}
```

```mermaid
graph LR
A[你的年齡] --> B{是否成年}
B --> |是| C[你已經成年了]
B --> |否| D[你還未成年]
```

上面的例子用到一些簡單的判斷式，我們會在教學的後面章節中介紹。在這裡，我們只需要知道，如果 `age` 大於等於 18，則會輸出 `你已經成年了`，否則輸出 `你還未成年`。