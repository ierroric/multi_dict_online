# multi_dict_online
自定义字典
目的：想在网页上搜索一次单词，出现多个结果。结果1有道界面，结果2百度site搜索词源，结果3，按照单词软件形式来展现出结果。根据单词磁性改变背景图案。

思路：1、按照fairydiction的方式，点击按钮弹出对应的网页（已实现），问题：弹出的网页还是有些麻烦，浏览器会阻拦，如果弹出的网页是2分屏就好了。

          2、常规在线词典实现方式。，对新查询的内容多一个入库，查库，删库的动作，构建查询出内容在一个网页上的显示

技术基础：

1、单纯html页面

2、WordPress建站

如何在网页上增加搜索框，这个我就是有点不会了。（已会，需深挖）

3、易用性优化

实现：

按照fairydiction的方式，点击按钮弹出对应的网页

fairyDict 的源码，我在github上看了半天，说实话没看懂，大概清楚是点击搜索弹出网页的方法来实现的，但具体实现方法看不懂。。

 https://github.com/revir/FairyDict  

  建瓴 的博客内容，把要实现的内容都实现了，他还实现了搜索建议，主要是，他的实现方式是比较像伪代码，直接复制反而不能运转。

https://blog.csdn.net/lixiaobuaa/article/details/76074963 

百度搜索api

 https://blog.csdn.net/qq_29654777/article/details/104051567 

基本链接1http://www.baidu.com/s?wd=关键字&cl=类型&pn=页码&ie=gb2312&rn=显示条数&tn=原站点

基本链接2https://www.baidu.com/s?q1=主关键词&q2=&q3=&q4=&gpc=stf&ft=&q5=&q6=news.sina.com.cn

原文链接：https://blog.csdn.net/qq_29654777/article/details/104051567

encodeURIComponent decodeURIComponent 

https://blog.csdn.net/li2327234939/article/details/53675211 

html 注释

 https://www.w3school.com.cn/html/html_comments.asp 

html中如何加入JavaScript （在head中 script标签）

 https://blog.csdn.net/twc829/article/details/51325853 

用<input>来实现搜索框，按钮， value来传递和设置参数

 hhttps://www.w3school.com.cn/jsref/prop_text_value.asp 

按钮按键事件

 https://www.w3school.com.cn/jsref/met_button_click.asp 

技术参考：

我的大概思路就是，应该是从数据库调用数据是吧。。。

fairydiction 源码  https://zhuanlan.zhihu.com/p/26692062 

 https://zhuanlan.zhihu.com/p/134119867 

其他在线词典网站，主要是直接看网站其实不知道是如何运作的

可以碰瓷的人

 garypang   https://www.pdawiki.com/forum/space-uid-199595.html 

 hua  https://forum.freemdict.com/t/topic/1784 

路径记录

 本地搭建wordPress

 https://zhuanlan.zhihu.com/p/32473851 

 https://www.jianshu.com/p/cbd86e09361d 

在服务器上搭建wordPress

 https://themeforwp.net/archives/wordpress-website-tutorial/ 

 https://medium.com/@jackme256/wordpress-%E5%BB%BA%E7%AB%99%E6%95%99%E7%A8%8B-%E6%96%B0%E6%89%8B%E6%90%AD%E5%BB%BA-wordpress%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2%E5%9B%BE%E6%96%87%E6%95%99%E7%A8%8B-%E5%AE%8C%E5%85%A8%E7%89%88-62ffd287f756 

与xampp相比还有哪些工具

 https://www.lovecoder.cn/1790.html 

用xampp建自定义网站

 https://jingyan.baidu.com/article/17bd8e5268584685ab2bb8d5.html 

修改wordPress（在干，以上都已经总结好）

 https://www.php.cn/cms/wordpress/425651.html 

 https://www.zhihu.com/question/36022499/answer/92508503 

 https://www.php.cn/cms/wordpress/425509.html 

 https://www.wpdaxue.com/wordpress-new-page.html 

 https://wpshushu.com/ 
