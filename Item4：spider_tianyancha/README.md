### 项目总述：
这个项目写了2个爬虫

- 第一个是在python2_tianyancha文件中，是使用的是python2，请求库是requests
- 第二个是在scrapy3_tianyancha文件中，是使用的是python3，用scrapy框架写的

刚开始用的是requests写的爬虫，但是思路不够严谨，在加上没有加协程，爬取的效率很低，之后将代码迁到scrapy框架中，准确度、效率和容错率都提高了很多

**具体信息见各个爬虫文档**

**（注意：由于项目中涉及到数据库，代理，钉钉等私密信息已经被隐藏，直接运行是不可能的，所以此项目仅供参考）**