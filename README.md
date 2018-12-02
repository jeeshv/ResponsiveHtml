# 响应式理财页面

无框架纯html5代码

## html5 大纲生成页面

https://gsnedders.html5.org/outliner/，另外webStorm自带了大纲生成工具，大纲让页面结构更加清晰


## html5 css查询网址

caniuse.com

## 前端原型设计工具
http://www.axure.com.cn

## 前端切图工具
photoshop

## 前端交互设计
http://www.principleformac.com


## 如何让 select的那个请选择不被选中.获取选中的value值和html
	<select   class="A">
		<option value=""  style="display:none” >请选择你最喜欢的水果</option>
		<option  value="1">苹果</option>
		<option  value="2">香蕉</option>
		<option  value="3">菠萝</option>
	</option>


	选择的时候显示的是 html的内容。水果的名字。
	获取到1.2.3     $(".A").val()
	获取苹果 香蕉 菠萝        
	$(":selected").html()
--------------------- 