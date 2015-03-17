### html规范
1. 使用html5的规范<!DOCTYPE html>
2. 注意html标签行为与语义，`<li onclick=”goToRecommendations();”>All recommendations</li>`应该写为`<a href=”recommendations/”>All recommendations</a>`
3. 多媒体标签向后兼容，记得加上alt属性
4. 由于utf-8编码的使用，某些记号无需转码，如`&mdash;`, `&rdquo;`, or `&#x263a;`当然<或是&除外
5. 注意HTML5 specification?中规定的可省略标签
6. type属性不要使用！HTML5中已经规定为默认且无必要
7. 为block标签另起一行，li出现例外可以放在一行

### css规范

1. 正确使用缩写，例如navigation就可以缩写为nav，而author就不要缩写
2. id与类名前不必加上标签类型
3. 属性尽量使用简写形式，如font或background等
4. 0后面不要加上单位
5. 小数前不要加上0
6. url()中不要加入引号，例如@import url(//www.google.com/css/go.css);
7. 16进制尽量使用3位表示
8. 可以为项目加入前缀，例如.adw-help {} /* AdWords */
9. 分词使用“-”，如前例
10. 属性采用字典序申明，包括前缀如moz安排在webkit之前
11. {}里面都应该使用缩进，包括属性申明或另一个{}
12. 属性：与值之间用一个空格分开，例如font-weight: bold;
13. 为每个选择符及每个属性申明单独使用一行
14. 规则之间用一个空行分开

### css书写顺序

1. 位置属性(position, top, right, z-index, display, float等)
2. 大小(width, height, padding, margin)
3. 文字系列(font, line-height, letter-spacing, color- text-align等)
4. 背景(background, border等)
5. 其他(animation, transition等)

### id的命名
(1)页面结构 
*    容器: container 
*    页头：header 
*    内容：content/container 
*    页面主体：main 
*    页尾：footer 
*    导航：nav 
*    侧栏：sidebar 
*    栏目：column 
*    页面外围控制整体布局宽度：wrapper 
*    左右中：left right center 
(2)导航 
* 导航：nav 
* 主导航：mainbav 
* 子导航：subnav 
* 顶导航：topnav 
* 边导航：sidebar 
* 左导航：leftsidebar 
* 右导航：rightsidebar 
* 菜单：menu 
* 子菜单：submenu 
* 标题: title 
* 摘要: summary 
(3)功能 
* 标志：logo 
* 广告：banner 
* 登陆：login 
* 登录条：loginbar 
* 注册：regsiter 
* 搜索：search 
* 功能区：shop 
* 标题：title 
* 加入：joinus 
* 状态：status 
* 按钮：btn 
* 滚动：scroll 
* 标签页：tab 
* 文章列表：list 
* 提示信息：msg 
* 当前的: current 
* 小技巧：tips 
* 图标: icon 
* 注释：note 
* 指南：guild 
* 服务：service 
* 热点：hot 
* 新闻：news 
* 下载：download 
* 投票：vote 
* 合作伙伴：partner 
* 友情链接：link 
* 版权：copyright 
