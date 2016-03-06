# Markdown语法
## 标题
在文字前面加上# 即可
> \# 一级标题  
> \## 二级标题

    # 一级标题
    ## 二级标题

## 列表
    有序列的使用数字加点，无序列的使用*加空格
    >\*   
    >1.
## 引用
行首添加> 标示引用
>这是引用

## 分割线
一行连续使用三个以上-或*

## 链接
两种链接方式Inline和Reference
* 文字链接  
>Inline:  
\[谷歌](https://www.google.com)<br>
Reference:  
\[谷歌][google_url]
\[google_url]:https://www.google.com

* 图片链接  
和文字链接很像，区别在前面加上一个！

## 代码
使用```并在第一行指定语言将代码包裹起来<br>
或者使用Tab缩进后贴上代码

```java 
public class HelloWorld
{
    public static void main(String[] args)
    {
        System.out.println("Hello World!");
    }
}```

## 换行  
如果另起一行只需要在当前结尾加上两个空格  

##表格  
    |ABCD|EFG|HI|
    |----|:---:|:--|
    |1|2|3|
    |AAAA|BBB|CC|
    |5|6|7
|ABCD|EFG|HI|
    |----|:---:|:--|
    |1|2|3|
    |AAAA|BBB|CC|
    |5|6|7
    
## 转义字符  
使用特殊字符，如 \*\#\>之类的需要在前面加上\



