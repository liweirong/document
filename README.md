# document
搜集的一些文档

大标题  
===================================  
  大标题一般显示工程名,类似html的\<h1\><br />  
  你只要在标题下面跟上=====即可  
  
    
中标题  
-----------------------------------  
  中标题一般显示重点项,类似html的\<h2\><br />  
  你只要在标题下面输入------即可  
    
### 小标题  
  小标题类似html的\<h3\><br />  
  小标题的格式如下 ### 小标题<br />  
  注意#和标题字符中间要有空格  
  
### 注意!!!下面所有语法的提示我都先用小标题提醒了!!!   
  
### 单行文本框  
    这是一个单行的文本框,只要两个Tab再输入文字即可  
          
### 多行文本框    
    这是一个有多行的文本框  
    你可以写入代码等,每行文字只要输入两个Tab再输入文字即可  
    这里你可以输入一段代码  
  
### 比如我们可以在多行文本框里输入一段代码,来一个Java版本的HelloWorld吧  
    public class HelloWorld {  
  
      /**  
      * @param args  
   */  
   public static void main(String[] args) {  
   System.out.println("HelloWorld!");  
  
   }  
  
    }  
### 链接  
1.[点击这里你可以链接到www.google.com](http://www.google.com)<br />  
2.[点击这里我你可以链接到我的博客](http://guoyunsky.iteye.com)<br />  
  
###只是显示图片  
![github](http://github.com/unicorn.png "github")  
  
###想点击某个图片进入一个网页,比如我想点击github的icorn然后再进入www.github.com  
[![image]](http://www.github.com/)  
[image]: http://github.com/github.png "github"  
  
### 文字被些字符包围  
> 文字被些字符包围  
>  
> 只要再文字前面加上>空格即可  
>  
> 如果你要换行的话,新起一行,输入>空格即可,后面不接文字  
> 但> 只能放在行首才有效  
  
### 文字被些字符包围,多重包围  
> 文字被些字符包围开始  
>  
> > 只要再文字前面加上>空格即可  
>  
>  > > 如果你要换行的话,新起一行,输入>空格即可,后面不接文字  
>  
> > > > 但> 只能放在行首才有效  
  
### 特殊字符处理  
有一些特殊字符如<,#等,只要在特殊字符前面加上转义字符\即可<br />  
你想换行的话其实可以直接用html标签\<br /\>

# readme小技巧
[更多readme小技巧](https://blog.csdn.net/kaitiren/article/details/38513715 )


规范的README文件开头都写上一个标题，这被称为大标题。
在文本下面加上 等于号 = ，那么上方的文本就变成了大标题。等于号的个数无限制，但一定要大于0个哦。。
[百度](http://baidu.com "悬停显示")
 ## 插入图片
 ![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")  
  ### 插入GitHub仓库里的图片
 "https://github.com/ 你的用户名 / 你的项目名 / raw / 分支名 / 存放图片的文件夹 / 该文件夹下的图片"
  
 ## 给图片加上超链接
  [![baidu]](http://baidu.com)  
  [baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo"  
