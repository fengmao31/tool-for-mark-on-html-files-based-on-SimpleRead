# tool-for-mark-on-html-files-based-on-SimpleRead

简阅作者功能更新赶不上我用于学习的速度，所以把Google浏览器下载下来的插件缓存改了一些代码增加了一些功能。我讨厌把页面转成pdf上面标记，感觉还是html更方便。由于简阅2.0没开源，寻找堆成一团js代码的语句简直快瞎了狗眼。

# 新增功能

1. 简阅之后出现原文地址而且页面最上方，

2. 打开本地html并标注。

不过有点小问题是必须点一下标注才能启动标注，然后页面突然变大。本地html打开后似乎因为插件权限问题会改变字体颜色，但是原文件和简悦后不受影响。

3. 本地html标注后二次简阅和打印，不会循环加页头和页尾。
 
不过有点小问题是页面会突然变大。

希望能帮助其他搞科研的同行者。希望有大佬能够从zetro的谷歌插件改装可以保存离线html至zetro中。

# 使用方法

由于简阅SimpleRead是收费的谷歌插件，所以首先得买个正版SimpleRead2.0。当然原本作者的1.0版本除了没有标注系统是免费的，感谢简阅的作者。

Google浏览器右键管理扩展程序，加载已解压的扩展程序，加载就可以了。因为Google浏览器不允许安装非商店的插件，所以没法封装程crx安装了。

需要使用两个简阅，一个用于第一次导出，一个用于以后标注和导出。因为标注和导出会导致循环加SimpleRead页头和页尾，而我又不想在推成一团的js中写js代码（当然我也不会js代码）。

# 简悦官方链接

1. 简悦的官网链接 http://simpread.pro/

2. 简悦 2.0 的购买链接 https://simpread.pro/price.html
