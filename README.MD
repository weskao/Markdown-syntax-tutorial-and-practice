# 標題

# h1

## h2

### h3

#### h4

##### h5

###### h6

## MyHeader

### Header3

## 分隔線 (下一行必須有一個Enter)

---

*斜體 (italics)*

**粗體 (bold)**

~~刪除線 (strikethrough)~~

## 有序清單(Ordered list)

1. Item1
2. Item2

## 無序清單(Non-Ordered list)

- Item1
- Item2

## 有序清單 搭配 無序清單

1. Item1
   - Inline Item1
   - Inline Item2
2. Item2

## 任務列表

- [ ] A任務
- [ ] B任務
- [x] C任務
- [ ] D任務

## 引用

> 文字內容
>> 縮排
>>> 再縮排 (依此類推)

(結束引用)

## 等寬字

`word123123ABSDF (將每個英文字都做到相同的寬度)`

## 程式碼區塊 (Code block)

```CSharp
using System;

namespace ConsoleApplication
{
    public class Program
    {
        private static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
            Console.ReadLine();
        }
    }
}
```

## 表格 (Table)

|Name|Sex|Age|Country|
|---|----|----|---|
|Bruce|Male|26|Taiwan|Unknown|
|Tina|Female|22|Japan|Remark~~~|
|ZZZ|XXX|999|Universe||

## 圖片 (Image)

### From relative path (圖片路徑不可包含"空白"!!!)

![GitHub Image from local](Images/GitHub_Icon.png)

滑鼠移到圖片上會有文字顯示:
![GitHub Image from local](Images/GitHub_Icon.png "Github")

### 　From website link

![GitHub Image from website](https://i.imgur.com/XGu8q8s.png)

### Click image to go to certain page

[![Github - Home Page](https://i.imgur.com/XGu8q8s.png)](https://github.com/ "Click here to browse Github home page")

## 超連結 (Hyperlink)

<https://markdown.tw/>

[Google](http://www.google.com/)

There will appear a tooltip when your cursor hover on this link.
[Google](http://www.google.com/ "A search engine")

## 數學 (Math)

行內公式示範：$123$

另一個例子：$a^2 + b^2 = c^2$

獨立一行公式：
$$
E = mc^2
$$

- 平方 → $a^2$
- 開根號 → $\sqrt{a}$
- 分數 → $\frac{a}{b}$
- 無限大 → $\infty$

### **常見數學表示法 (Math in Markdown/LaTeX)**

#### 1. 上下標

$a^2$   →  \( a^2 \)
$a^{10}$ →  \( a^{10} \)
$x_i$   →  \( x_i \)

#### 2. 開根號

$\sqrt{4}$    →  \( \sqrt{4} \)
$\sqrt{a^2+b^2}$ →  \( \sqrt{a^2+b^2} \)
$\sqrt[3]{8}$ →  \( \sqrt[3]{8} \)   （三次方根）

#### 3. 分數

$\frac{1}{2}$    →  \( \frac{1}{2} \)
$\frac{a+b}{c+d}$ →  \( \frac{a+b}{c+d} \)

#### 4. 希臘字母

$\alpha, \beta, \gamma, \pi, \theta, \Omega$
→  \( \alpha, \beta, \gamma, \pi, \theta, \Omega \)

#### 5. 公式 (行內與區塊)

行內：$E=mc^2$ → \( E=mc^2 \)

區塊：
$$
\int_0^\infty e^{-x}\, dx = 1
$$

#### 6. 常用符號

$\pm$ → \( \pm \)
$\times$ → \( \times \)
$\div$ → \( \div \)
$\infty$ → \( \infty \)
$\leq, \geq$ → \( \leq, \geq \)

## Go to Header (only works in browser)

- [Go to h1](#h1)
- [Go to myHeader](#myheader)
- [Go to header3](#header3)
- [Go back to top of page](#start-of-content)

## Videos

<div>
    <video id="video" controls="" preload="none" poster="http://media.w3.org/2010/05/sintel/poster.png">
        <source id="mp4" src="http://media.w3.org/2010/05/sintel/trailer.mp4" type="video/mp4">
        <source id="webm" src="http://media.w3.org/2010/05/sintel/trailer.webm" type="video/webm">
        <source id="ogv" src="http://media.w3.org/2010/05/sintel/trailer.ogv" type="video/ogg">
        <p>Your user agent does not support the HTML5 Video element.</p>
    </video>
</div>
