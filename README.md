# Broadcast
轮播图的各种实现
网页效果预览链接：
http://htmlpreview.github.io/?https://github.com/mingxinZ/Broadcast/blob/master/%E5%8E%9F%E7%94%9FJS%E5%86%99%E8%BD%AE%E6%92%AD%E5%9B%BE.html
实现的功能：
1.进入页面自动播放；
2.无缝衔接播放；
3.当鼠标放在图片上，停止自动播放并且显示左右焦点；
4.当鼠标离开图片，左右焦点消失；
5.点击左右焦点翻到上一张或者下一张图片。
在写代码中遇到的问题：
1.创建属性的时候，属性的值应该是数字类型，而不是字符串类型。
liObj.setAttribute("index",i);
我写成了：
liObj.setAttribute("index","i");
2.在第172行和第194行代码中，pic后面的等于号应该只有一个，我写成了两个，我想让它们严格等于。但是在赋值情况下只能写一个等于号。
