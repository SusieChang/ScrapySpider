#### 项目概要
论文数据爬取并清洗，存储到数据库
#### 爬取内容
1. 爬取万方数据的关键信息，包括：
- 标题(中/英)
- 作者(中/英)
- 关键词(中/英)
- 摘要(中/英)
- 出版日期
- doi
- 文章链接
- 搜索关键词

2. 爬取知网数据的关键信息，包括：
- 标题(中or英)
- 作者(中or英)
- 关键词(中or英)
- 摘要(中or英)
- 出版日期
- 论文类型
- 文章链接
- 搜索关键词

#### 运行
cd Scrapy/myspider
python run.py + 爬虫名字(cnki/wapcnki/wanfang)
-k 关键词
-m 最大页数
-h 帮助
