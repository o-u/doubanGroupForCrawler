doubanGroupForCrawler
=====================

项目的作用是 爬取豆瓣上海租房小组

###
    暂时考虑用tornado 和 mongodb 这两个工具。
    现在主要的思路是
    先爬取最新的信息，存在数据库
    然后另外一个机器人根据标题 进行聚类，给每个租房的帖子打上标签
    另外一个爬取帖子里面的内容 提取主要信息 地点 价格 联系方式 等等。
    tornado展示。
