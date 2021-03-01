JQuery:
    主要函数 : $(function()){  //意味着在页面加载完之后执行相当于window.onload=function(){}
                    //要执行的方法 : #(选择器).方法(function(){方法体})
                    #("btn").click(function(){
                        //具体执行;
                    })
               }
    $(“#id 属性值”); id 选择器，根据 id 查询标签对象
    $(“标签名”); 标签名选择器，根据指定的标签名查询标签对象
    $(“.class 属性值”); 类型选择器，可以根据 class 属性查询标签对象


    DOM对象和JQuery对象 :
        DOM 对象 Alert 出来的效果是：[object HTML 标签名 Element]
        jQuery 对象 Alert 出来的效果是：[object Object]
        JQuery对象本质: jQuery 对象是 dom 对象的数组 + jQuery 提供的一系列功能函数。

    JQuery中的选择器 :
        1.基本选择器 : 重-------
            #ID 选择器                         ：根据 id 查找标签对象
            .class 选择器                      ：根据 class 查找标签对象
            element 选择器                     ：根据标签名查找标签对象
            * 选择器                           ：表示任意的，所有的元素
            组合选择器                         ：合并选择器 1，选择器 2 的结果并返回  $("选1,选2...")
        2.层级选择器 : 重--------
            ancestor descendant 后代选择器 ：在给定的祖先元素下匹配所有的后代元素
            parent > child 子元素选择器：在给定的父元素下匹配所有的子元素
            prev + next 相邻元素选择器：匹配所有紧接在 prev 元素后的 next 元素
            prev ~ sibings 之后的兄弟元素选择器：匹配 prev 元素之后的所有 siblings 元素
        3.过滤选择器 : 重--------
            :first 获取第一个元素
            :last 获取最后个元素
            :not(selector) 去除所有与给定选择器匹配的元素
            :even 匹配所有索引值为偶数的元素，从 0 开始计数
            :odd 匹配所有索引值为奇数的元素，从 0 开始计数
            :eq(index) 匹配一个给定索引值的元素
            :gt(index) 匹配所有大于给定索引值的元素
            :lt(index) 匹配所有小于给定索引值的元素
            :header 匹配如 h1, h2, h3 之类的标题元素
            :animated 匹配所有正在执行动画效果的元素
        4.内容过滤器 :
            :contains(text) 匹配包含给定文本的元素
            :empty 匹配所有不包含子元素或者文本的空元素
            :parent 匹配含有子元素或者文本的元素
            :has(selector) 匹配含有选择器所匹配的元素的元素
        5.属性过滤器 :
            [attribute] 匹配包含给定属性的元素。
            [attribute=value] 匹配给定的属性是某个特定值的元素
            [attribute!=value] 匹配所有不含有指定的属性，或者属性不等于特定值的元素。
            [attribute^=value] 匹配给定的属性是以某些值开始的元素
            [attribute$=value] 匹配给定的属性是以某些值结尾的元素
            [attribute*=value] 匹配给定的属性是以包含某些值的元素
            [attrSel1][attrSel2][attrSelN] 复合属性选择器，需要同时满足多个条件时使用。
        6.表单过滤器 :
            :input 匹配所有 input, textarea, select 和 button 元素
            :text 匹配所有 文本输入框
            :password 匹配所有的密码输入框
            :radio 匹配所有的单选框
            :checkbox 匹配所有的复选框
            :submit 匹配所有提交按钮
            :image 匹配所有 img 标签
            :reset 匹配所有重置按钮
            :button 匹配所有 input type=button <button>按钮
            :file 匹配所有 input type=file 文件上传
            :hidden 匹配所有不可见元素 display:none 或 input

