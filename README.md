# 汽车之家爬虫
这个爬虫可以用于从汽车之家批量获取关于某一车型的评论，可以用于进一步的自然语言分析
# 配置需求
本爬虫用python编写，在python3.5上测试运行正常，使用到的包如下：
```
from selenium import webdriver
from bs4 import BeautifulSoup
import json
import time
```
# 获取的数据
运用本爬虫，可获得以下数据：相关车型论坛中的评论数据，相关车型的口碑数据，相关车型的各单项评分。
