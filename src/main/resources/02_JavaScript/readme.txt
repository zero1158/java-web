JavaScript :
    1.在html中使用js的方式:
        1.在 head标签中,或者在body标签中,使用script标签来书写JavaScript代码
        2.使用script标签来引入单独的js文件
        注意 :
            1.不能在同一个script标签中使用上述两种方式
            2.当两者同时存在的时候(多个script标签),在head标签中的会依次执行

    2.1.js中的变量类型 :
        数值类型   : number
        字符串类型 : string
        布尔类型   : boolean
        对象类型   : object
        函数类型   : function
    2.2.js中的特殊值 :
        null : 空值
        undefined : 未定义,所有js变量为赋予初始值时默认为undefined
        NuN : not a number 非数字
    2.3.js中的比较关系符 :
        == : 只做简单的字面值比较
        ===: 除了比较字面值以外还会比较两个变量的数据类型

    2.4.逻辑运算 ：在 JavaScript 语言中，所有的变量，都可以做为一个 boolean 类型的变量去使用
        且运算： &&
        或运算： ||
        取反运算： !
        注意 ： 0 、null、 undefined、""(空串) 都认为是 false

    3.数组及函数 : 重点
        var 数组名 = []; // 空数组
        var 数组名 = [1 , ’abc’ , true]; // 定义数组同时赋值元素
        var arr2 = new Array(5);//创建指定长度的数组

        函数(重点) : 定义函数的两种方式
        注：在 Java 中函数允许重载。但是在 JS 中函数的重载会直接覆盖掉上一次的定义
            1.function 函数名(形参列表){
                    函数体
              }
            2.var 函数名 = function(形参列表) { 函数体 }





