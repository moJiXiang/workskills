>Javascript will be used in font-end work.It will also be used in prophase `mininum viable product` after-end development.I will learn google font-end precification and use it.

> Any violation to this guide is allowed if it enhances readability. 
所有的代码都要变成可供他人容易阅读的。 
–引用自Dojo Javascript 语法规范

1. 变量声明必须使用var
2. 记得使用分号结尾
3. eval只用于rpc解码json，注意
4. for in 不要用在遍历array上，只能用在object上
5. 多行的字符串字面量，应该使用+进行字符串拼接，而不是进行换行
6. 命名：functionNamesLikeThis,variableNamesLikeThis,ClassNamesLikeThis,EnumNamesLikeThis,?methodNamesLikeThis, and SYMBOLIC_CONSTANTS_LIKE_THIS.
7. 私有成员使用结尾下划线(trailing undercore)，保护成员不使用结尾下划线；可选参数以opt_开头，如果函数有可变参数，则最后一个参数命名为var_args，但不要使用他而要使用arguments数组进行访问；不要使用get和set关键字，如果要写则使用getFoo();setFoo(val);isFoo()的形式；
8. 永远要为项目添加一个命名空间，不要为外部引入的代码再引入自定义的成员，如果必要则应该使用外部代码暴露的api
9. 文件命名统一使用小写”.js”，同时推荐”-“而不是”_”
10. 技巧：
    关于boolean，下面这些为false
        null
        undefined
        ''空字符串
        数字0
    但是注意这些为true
        '0' 字符
        [] 空数组
        {} 空对象
11. 公有方法和属性 混合，例子：mixedCase 
私有方法和属性 混合，例子：_mixedCase 
方法（method）参数 混合，例子：mixedCase 
本地（local）变量 混合，例子：mixedCase 

### 注释规范

1. 一些你不打算给其他人使用的函数，建议添加 @ignore 让文档输出时可以忽略这段注释 
2. 一些相关的功能相关的函数，建议加上@see Function 来对上下文做索引 
3. 对于一些函数不建议或则需要注意的使用方法，必须加上 @deprecated作为提醒 
4. 每个js文件的文件头都必须包含 @fileoverview @author , 建议加上@version 
5. 每个函数都必须使用JsDoc 来注释他的用意 
6. 每个带参数的函数必须包含 @param 
7. 每个有返回值的函数必须包含 @return 
8. 构造函数必须加上 @constructor 
9. 继承函数建议加上 @base 表示其继承于哪个类 
10. 常用全局变量建议使用 JsDoc 的注释方式 
11. 一般的变量及局部变量才用 // 方式进行注释，建议在需要做注释的语句的上一行 

