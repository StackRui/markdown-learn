# Markdown 语法

## 删除线
~~hello~~

## 列表
1. 你好
2. 我好
3. 大家好

* 他好
* 我才好
* 会元牌肾宝

+ 大爷，
+ 楼上322是马冬梅家么？
+ 什么冬梅啊？
+ 马冬梅啊
+ 马什么梅啊？
+ 马冬梅啊！
+ 马冬什么啊？
+ 行了，大爷您凉快会儿吧

## 斜体
*hi*

## 粗体
**hi**

## 粗斜体
***hi***

## 下划线
<u>hi</u>

## 脚注
This is a sentence with a[^1] footnote.

[^1]: This is the text of the footnote.

## 代码
  ```
  console.log("");
  ```
## 分割线
***
* * *
******
- - -
_ _ _

## 区块
> 区块一  
>> 区块二  
>>> 区块三

## 代码区块
    <?php
      function test() {
        echo 'hello, world';
      }
      test()
    ?>   

```java
    public class HelloWorld {
    
    public static void main(String[] args) {
            System.out.println("hello, world");
        }
    }
```
## 链接
[腾讯网](https://www.qq.com)  
或
<https://www.qq.com>

[访问腾讯网请点击][qq.com]  

[qq.com]: https://www.qq.com

## 图片
![logo](https://inews.gtimg.com/newsapp_bt/0/12171811596_909/0)

链接也可以用变量来替代，文档末尾附带变量地址：

![logo][1]

[1]: https://inews.gtimg.com/newsapp_bt/0/12171811596_909/0

<img src="https://inews.gtimg.com/newsapp_bt/0/12171811596_909/0" width=50%>

## 表格
| 表头 | 表头 |
| --- | --- |
| 单元格 | 单元格 |
| 单元格 | 单元格 |

| 左对齐 | 右对齐 | 居中对齐 |
| :---- | ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

## HTML
使用 <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Del</kbd> 来重启电脑   
<b>加粗的字体</b>  
<i>斜体字</i>  
<em>强调文本</em>  
这个文本包含<sup>上标</sup>文本  
这个文本包含<sub>下标</sub>文本  
使用 br 元素<br>在文本中<br>换行  

## 转译
* \   反斜线
* `   反引号
* \*  星号
* _   下划线
* {}  花括号  
* []  方括号  
* ()  小括号
* \#   井字号
* \+   加号
* \-   减号
* .   英文句点
* !   感叹号

**文本加粗**  
\*\*正常显示星号\*\*

## 高级技巧-数学公示
$$(x^2 + x^y )^{x^y}+ x_1^2= y_1 - y_2^{x_1-y_1^2}$$

