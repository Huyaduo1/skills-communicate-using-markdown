# 欢迎来到我的博客

<style>
/* 全局样式设置 */
body {
  font-family: "KaiTi", "楷体_GB2312", sans-serif;  /* 楷体字体（带中文fallback） */
  color: #000000;                   /* 纯黑色文字 */
  background-color: #F0FFF4;        /* 浅绿色背景（可替换其他浅绿色值） */
  margin: 1em;                      /* 保持原有边距 */
}
</style>

# 这是一个标题

这是正文内容，会继承全局样式设置。

我看到了不少开源的构建个人博客的项目，所以打算自己写一个
它现在是<font color="red">简陋的</font>，但是之后到暑假了我会<font color="red">更新</font>它，并构建一些可以交互的页面，更换一个方便好记的的域名。

现在先放一些文字，图片，视频，链接来试一下这个网页。

##  头像
下面是我的头像

![图片名](https://avatars.githubusercontent.com/u/211213103?v=4)

## 做个任务列表
```c
//- [ ] 输入你的内容
```
- [ ] 和宇宙荣耀maze哥哥打游戏
- [ ] 复习期末考试
- [ ] 吃一碗猪脚饭，发誓要挣一百万

注意这是看网图，不是我对象，我对象更好看

<img src="https://raw.bgithub.xyz/Huyaduo1/skills-communicate-using-markdown/refs/heads/master/hhh.jpg">


## 插入一段视频 看坤坤跳舞

<img src="https://p11-sign.douyinpic.com/obj/douyin-user-image-file/99f82e528751af6f4ef351e1c4d9c615?lk3s=7b078dd2&x-expires=1747065600&x-signature=IHuUHZG5Ntc5qgW42KIAY9T7260%3D&from=2064092626&s=sticker_comment&se=false&sc=sticker_heif&biz_tag=aweme_comment&l=20250512185631F7A2C86C9AB4463C8D65">

好了正片来了，Git上传的视频文件有问题，这里放一个b站开源的（垃圾抖音）

<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=984714877&bvid=BV1ct4y1n7t9&cid=807427488&p=1" allowfullscreen="allowfullscreen" width="100%" height="500" scrolling="no" frameborder="0" sandbox="allow-top-navigation allow-same-origin allow-forms allow-scripts"></iframe>

## 上链接，听歌

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=475479888&auto=1&height=66"></iframe>



## 添加C语言的一个代码块

<button type="button" onclick="alert('Hello World!')">点击这里</button>

```C
#include<stdio.h>
int main()
{
  printf("hello world");
  return 0;
}
```
这是javascript的，好像看不出来风格有什么不同
``` javascript
var myVar = "Hello, world!";
```

效果不错欧

<table>
    <tr>
        <td>接下来干点什么好呢</td>
    </tr>
</table>


 
$\alpha$
$\beta$
$\chi$
$\Delta$
$\Gamma$
$\Theta$

#### 写几个数学公式

 $$
 \sin^2(\theta) + \cos^2(\theta) = 1
 $$
 
 $$
 \sum_{n=1}^\infty k
 $$
 
 $$
 \int_a^bf(x)\,dx
 $$
 
 $$
 \lim\limits_{x\to\infty}\exp(-x) = 0
 $$
 
#### 写个矩阵
$$
 \left|\begin{matrix}
    a & b & c \\
    d & e & f \\
    g & h & i
   \end{matrix} \right|
 $$

<table>
    <tr>
        <td>Markdown还可以干什么呢，试一下内嵌的HTLM吧</td>
    </tr>
</table>


<!DOCTYPE html>
<html>
<head>
  <!-- 引入MathJax 3库（CDN） -->
  <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
  
  <!-- MathJax配置 -->
  <script>
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']],
      packages: {'[+]': ['physics']}  // 可选：扩展包（如需要特殊符号）
    },
    svg: {
      fontCache: 'global'
    }
  };
  </script>
</head>
<body>

<h4>希腊字母示例</h4>
<p>
  $\alpha$  $\beta$  $\chi$  
  $\Delta$  $\Gamma$  $\Theta$
</p>

<h4>数学公式示例</h4>

<p>三角恒等式：</p>
$$
\sin^2(\theta) + \cos^2(\theta) = 1
$$

<p>求和公式：</p>
$$
\sum_{n=1}^\infty k
$$

<p>定积分：</p>
$$
\int_a^b f(x)\,dx
$$

<p>极限：</p>
$$
\lim\limits_{x\to\infty} \exp(-x) = 0
$$

<h4>矩阵示例</h4>
$$
\left|
\begin{matrix}
  a & b & c \\
  d & e & f \\
  g & h & i
\end{matrix}
\right|
$$

</body>
</html>




<font face=" 楷体 ">我不是黑体字</font>


<table><tr><td bgcolor="#E6E6FA">这里的背景色是Lavender</td></tr></table>

<form action="#">
    <label for="name">姓名:</label>
    <input type="text" id="name" name="name"><br><br>
    <input type="submit" value="提交">
</form>

建议回去看看文章开头的 <a href="#applicable-situation">再看一遍</a>。
