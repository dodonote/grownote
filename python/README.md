
1.以r或R开头的python中的字符串表示（非转义的）原始字符串
2.以u或U开头的字符串表示unicode字符串

3.range（start， end， scan):

4.sys.getcwd() 输出当前目录地址
5.sys.path 输出当前目录现所有文件名称数组

6.重复操作符( * ) 
7.strip() 去除空格

列表

i = [ i * 2 for i in [8, -2, 5] ] 
	
print i

8.extract后会把selector对象转换成list类型了

9.Python通过re模块提供对正则表达式的支持。使用re的一般步骤是先使用re.compile()函数，将正则表达式的字符串形式编译为Pattern实例
import re
pattern = re.compile('[a-zA-Z]')
result = pattern.findall('as3SiOPdj#@23awe')
print result
# ['a', 's', 'S', 'i', 'O', 'P', 'd', 'j', 'a', 'w', 'e']



10.zlib.decompress 解压缩文件

11.模块 WordCloud 词云

12.yield scrapy.Request

13.python中，platform模块给我们提供了很多方法去获取操作系统的信息
    如：
        import platform
        platform.platform()   #获取操作系统名称及版本号，'Windows-7-6.1.7601-SP1'
        platform.version()    #获取操作系统版本号，'6.1.7601'
        platform.architecture()   #获取操作系统的位数，('32bit', 'WindowsPE')
        platform.machine()    #计算机类型，'x86'
        platform.node()       #计算机的网络名称，'hongjie-PC'
        platform.processor()  #计算机处理器信息，'x86 Family 16 Model 6 Stepping 3, AuthenticAMD'
        platform.uname()      #包含上面所有的信息汇总，uname_result(system='Windows', node='hongjie-PC',

14.使用代理文章 https://github.com/chenjiandongx/stackoverflow/blob/master/stackoverflow/middleware/httpproxy.py

15.使用 userAgant 
https://github.com/chenjiandongx/stackoverflow/blob/master/stackoverflow/middleware/useragent.py

16.Python strip() 方法用于移除字符串头尾指定的字符（默认为空格）。

17.unicodePage = myPage.decode("utf-8", 'ignore') decode 转换字符集

18.resp.text返回的是Unicode型的数据。

resp.content返回的是bytes型也就是二进制的数据。
也就是说，如果你想取文本，可以通过r.text。

如果想取图片，文件，则可以通过r.content。

（resp.json()返回的是json格式数据）

19.requirements.txt
安装 (venv) $ pip install -r requirements.txt
生成 pip freeze > requirements.txt

20.join 以空格相连 
   REDIS.set('keywords', ' '.join(keywords))

21.for i in range(1, 21): for 数组 从 1 到 21


python 爬虫项目

抓取地址列表：https://github.com/facert/awesome-spider

简单：自如实时房源提醒、网易云音乐
github_search https://github.com/facert/github_search

中等：豆瓣读书、链家、京东商品+评论、今日头条网易腾讯等新闻、github trending、新闻监控、前程无忧Python招聘岗位信息爬取分析、Shadowsocks 账号爬虫
网易新闻（mongo）

tumblr 多线程、天猫双12爬虫、Tmall 女性文胸尺码爬虫、电影网站、乌云公开漏洞

高级内容：https://github.com/yijingping/unicrawler 分布式抓取框架
https://github.com/bowenpay/wechat-spider 公众号抓取
微博主题搜索分析
知乎妹子





