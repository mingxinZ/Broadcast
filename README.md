# Broadcast
轮播图的各种实现</br>
网页效果预览链接：</br>
http://htmlpreview.github.io/?https://github.com/mingxinZ/Broadcast/blob/master/%E5%8E%9F%E7%94%9FJS%E5%86%99%E8%BD%AE%E6%92%AD%E5%9B%BE.html</br>
实现的功能：</br>
1.进入页面自动播放；</br>
2.无缝衔接播放；</br>
3.当鼠标放在图片上，停止自动播放并且显示左右焦点；</br>
4.当鼠标离开图片，左右焦点消失；</br>
5.点击左右焦点翻到上一张或者下一张图片。</br>
在写代码中遇到的问题：</br>
1.创建属性的时候，属性的值应该是数字类型，而不是字符串类型。</br>
liObj.setAttribute("index",i);</br>
我写成了：</br>
liObj.setAttribute("index","i");</br>
2.在第172行和第194行代码中，pic后面的等于号应该只有一个，我写成了两个，我想让它们严格等于。但是在赋值情况下只能写一个等于号。</br>
