jquery-1.11.3.min.js: 为JQuery核心压缩版库文件（可到http://jquery.com/自行下载）自行下载

jquery.mobile-1.4.5.min.js: 为JQuery Mobile的库文件，其中引用了JQuery核心库文件（可到http://jquerymobile.com/自行下载）

jquery.mobile-1.4.5.min.css: JQuery Mobile使用的样式表

images: 样式表使用的图片文件

1.将三个文件一个文件夹copy到工程里
2.注意在HTML里head里引入框架时先引入css文件，后引入JQuery核心文件，最后引进JQuery mobile
example：
<link rel="stylesheet" type="text/css" href="jquery.mobile-1.0.min.css">
<script src="jquery-1.6.4.min.js"></script>
<script src="jquery.mobile-1.0.min.js"></script>
3.开始编写代码

