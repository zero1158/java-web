HTML :
    1.熟悉html基本格式(见hello.html):
        <head><!--表示头部信息,一般包含三部分内容:title标签,css样式,js代码-->
        <title>这是一个标题</title><!--标题-->
        <body bgcolor="aqua" onclick="alert('单击主题页面')"><!--body标签是整个html显示的主体内容-->

    2.注意: 超链接标签,列表标签,跳转图片,表格标签,表单及表单提交(重要)的使用

CSS :
    1.注意css基本语法:
        选择器{
            属性1:值 值 ..;
            属性2:值;
        }
    2.使用css选择器的方式(见css基本语法) :
        1.在<div>直接设置(一般不用)
        2.在<head>标签内使用<style>标签
        3.单独在css文件中写,然后在html文件的<head>标签中使用 :
            <link rel="stylesheet" href="css文件路径" type="text/css">
    3.选择器的写法:
        1-标签名选择器 : div{..}
        2-id选择器 :
        3-.class选择器 :
        4-id,.class,...选择器

