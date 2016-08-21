# Real_Shadow
使一个元素的阴影随鼠标位置的改变而改变
[![Build](http://myweb-10017157.file.myqcloud.com/gif/131162438547733762.gif)]()

使用方法:

1.引入Real_Shadow文件
<script type="text/javascript" src="http://myweb-10017157.file.myqcloud.com/js/131162441704998594.js"></script>
2.然后这样写
' 
<span class="realshadow"></span>
<div class="inset">这是内阴影
<script type="text/javascript" src="realshadow.js"></script>
<script type="text/javascript">
	(function() {
		realshadow(document.getElementsByClassName('realshadow'));
		realshadow(document.getElementsByClassName('inset'), {inset: true});
	})();
</script>
	'
