## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Diaboluo/Diaboluo.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

<!DOCTYPE html>
<html>
 <head>
  <meta charset="utf-8">
  <title>this is title</title>
  <!-- style声明样式，即内联样式 -->
   <style type="text/css">
   /* 声明一个类 */
   .demo
   {
    color: black;
    /* 设置被类选择器选择中的p标签的文本颜色为黑色（black） */
    background-color:FFFFFF;
    /* 设置被类选择器选择中的p标签的背景颜色 */
   }
   /* 声明某个类被鼠标移入后改变的效果 */
   .demo:hover
   {
    background-color: #FFFACD;
    /* 鼠标移入后背景颜色发生改变 */
    color: Crimson;
    /* 设置被类选择器选择中的p标签的文本颜色为蓝色（FF9900） */
   }
  </style>
 </head>
 <body>
       <h1><center><b>Welcome to Su's homepage</b></center></h1>
       <hr size="5"  color="green"/> 
  <!-- 通过class类选择器选择demo类 -->
  <p class="demo"><font size=8>这是一个测试</font></p>
   <p class="demo" align="center"><font size=8>关于牛奶，点击一个</font></p>
 <hr size="5"  color="green"/> 
      <ol>
          <li><p class="demo" align="center"><a href="https://baike.baidu.com/item/%E7%89%9B%E5%A5%B6/28828?fr=aladdin" target="_blank"><font size=8>不喝</font></a></p></li>
          <br/>
          <li><p class="demo" align="center"><a href="http://www.4399.com" target="_blank"><font size=8>真香</font></a></p></li>
      </ol>  
 <hr size="5"  color="green"/> 
<audio autoplay="autoplay" loop="loop" preload="auto" controls="controls"
            src="http://music.163.com/song/media/outer/url?id=496869422.mp3">       
</audio>

 </body>
</html>
