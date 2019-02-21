# lianjia-spider
目录树：
lianjia-spider
├── bj_links.xlsx
├── bj_results.xlsx
├── font
│   └── msyh.ttf
├── lianjia_data.ipynb
├── map
│   └── json
│       └── province
│           └── beijing.json
├── mask.jpg
├── proxy.txt
├── stopword
│   └── 停用表.txt
└── word.jpg


★★★★★

在运行前请安装以下库：
requests、re、BeautifulSoup、numpy、pandas、matplotlib、seaborn、jieba、wordcloud、imageio、time、os、random

★★★★★
1.bj_links和bj_results文件为自带的数据集，是测试时爬取的北京全部数据，如需重新爬取或爬取其他城市则指定城市即可。

2.msyh.ttf为微软雅黑字体。

3.lianjia_data文件是botebook主文件。

4.map地图只有北京市。

5.mask.jpg 是生成词云图的蒙版图片。

6.proxy.txt代理IP文件，执行程序过程中，会重新爬取代理ip,生成proxy.txt文件。代理ip有时效性，所以没有自带代理ip文件，重新爬取即可。

7.stopword停用表，过滤分词时的无意义文字。

8.词云图生成的文件为word.jpg。

