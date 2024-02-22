# 69xinshu_spider

# 功能实现
+ 爬取69书吧排行榜的小说，并存入数据库，再用flask呈现再网页上

# 工具
+ python 3.10
+ flask web框架
+ mysql数据库

# 主要思路：
+ 通过spider.py将网站排行榜的小说的信息抓取至mysql数据库内，如小说正文，书名，作者名，简介
+ 通过app.py 使用flask web框架将数据库内数据渲染至网页端
+ 网页端功能实现
  + 收藏
  + 历史阅读
  + 小说阅读
  + 登录与注册 
