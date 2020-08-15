# 標題
# h1
## h2
### h3
#### h4
##### h5
###### h6

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

###　From website link
![GitHub Image from website](https://i.imgur.com/XGu8q8s.png)

### Click image to go to certain page

[![Github - Home Page](https://i.imgur.com/XGu8q8s.png)](https://github.com/ "Click here to browse Github home page")

## 超連結 (Hyperlink)

<https://markdown.tw/>

[Google](http://www.google.com/)

There will appear a tooltip when your cursor hover on this link.
[Google](http://www.google.com/ "A search engine")
