# demo_wechat
小程序

.js 后缀的是脚本文件
.json 后缀的文件是配置文件
.wxss 后缀的是样式表文件

微信小程序学习笔记

app.js 是小程序的脚本代码。我们可以在这个文件中监听并处理小程序的生命周期函数、声明全局变量。调用 MINA 提供的丰富的 API，如本例的同步存储及同步读取本地数据。
app.json 是对整个小程序的全局配置。我们可以在这个文件中配置小程序是由哪些页面组成，配置小程序的窗口  背景色，配置导航条样式，配置默认标题。注意该文件不可添加任何注释。
app.wxss 是整个小程序的公共样式表。我们可以在页面组件的class属性上直接使用app.wxss中声明的样式规则。

每一个小程序页面是由同路径下同名的四个不同后缀文件的组成，如：index.js、index.wxml、index.wxss、index.json。.js 后缀的文件是脚本文件，.json 后缀的文件是配置文件，.wxss 后缀的是样式表文件，.wxml 后缀的文件是页面结构文件。

1. "enablePullDownRefresh":true  下拉显示  "backgroundTextStyle":"dark",颜色设置要与背景色相异
2. appjson下tabBar的使用
3. index.json下的属性的使用，和app.json下window的使用一致
4. WXML 视图层   事件 事件的使用方式  
   数据绑定   在标签属性中设置时一定要加大括号。
   运算  三元运算  算数运算 逻辑判断
   列表渲染：wx:for
5. WXSS 是一套样式语言   相比CSS特性：rpx （尺寸单位），样式导入  (@import引入外联样式)
   内联样式
   全局样式，局部样式
6. 基本组件  text  hover-class的学习
7. 图片标签  image 是web中图片标签与背景图片的结合
8. 轮播图组件  swiper swiper-item 及其属性
9. 导航组件  页面链接 navigator
10. 视频组件 video
11. 自定义组件 component