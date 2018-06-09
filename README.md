# vague

预览地址
https://hakunamatata052.github.io/vague/

##使用方法
在页面中引入样式文件jQuery文件和插件js
<script src="js/jquery-1.7.2.min.js"></script>
<script src="js/vague.js"></script>

#HTML结构
你的html结构可以是任意结构，只需要img标签即可实现效果

例如：
<img src="images/bg4.jpg" alt="" title="" class="layer" />

#调用方法
$('.layer').vague();

可选参数
$('.layer').vague({
    size: 30, //放大镜的尺寸（单位：px）
    blur: 20  //模糊程度
});
