# FinalReader
a wenku8 Reader
这是一个轻小说文库的wap网页的本地化iOS应用，它所做的只有：

1.解析轻小说文库wap网页

2.下载和阅读轻小说

本应用只是一个基于个人爱好所写的iOS小应用，除代码内容属于本人所有，供爱好者学习交流，其余文字、图片、文档内容信息均归轻小说文库（www.wenku8.cn）解释与所有，请勿用于商业用途。

详细内容可以访问[wbuntu的博客](http://wbuntu.com/wordpress/?p=146)

支持的设备：iPhone5系列，包括iPod Touch5

系统要求：iOS8.0及以上（因为解析网页的部分使用了iOS8.0起提供的一些字符串处理函数）

这个小应用可以简单分成三部分：浏览、文件管理、阅读器

1.浏览

网页解析使用iOS内置的nsxml，继承nsxml自定义了多个用于解析的子类；

由于文库的文章信息和文章封面部分数据稳定，只缓存了这两部分；

所有内容参照wap网页的首页，还增加了一个搜索功能，也是基于wap网页。

2.文件管理

包括缓存文章简介与图片，下载、保存与删除小说，所有的小说全部采用分卷下载和gbk编码，使用了一个单例来完成所有工作。

3.阅读器

一个简单的阅读器，只有简单的阅读功能，小说打开时一次性分页，没有其他功能了，也是将来有时间会完善的部分。

