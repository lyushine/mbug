mbug
====

Mbug is a bug list for front-end development of mobile

## #1 页面高度渲染错误

   问题描述：页面100%高度包含地址栏高度，当地址栏存在时，会部分内容被隐藏
 环境与频率：经常性出现;各移动浏览器
   解决办法：重置<html>高度：document.documentElement.style.height = window.innerHeight + 'px'
 
## #2 叠加区高亮

   问题描述：使用click也会出现绑定点击区域闪一下的情况
 环境与频率：部分android机型
   解决办法：给该元素一个样式 -webkit-tap-highlight-color:Ωrgba(0,0,0,0);
