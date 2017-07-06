## 爬取知乎所有用户（crawler for zhihu users）

这篇教程是来自[静觅](http://cuiqingcai.com/4320.html)的视频教程写的，主要按照从社交网络某个节点出发进行爬取的思想，通过对知乎用户的关注者和关注的人进行递归地查询，从而迭代的进行爬取知乎用户。并且将爬取的用户信息存储在MongoDB中。



## Requirements

1. [Anaconda 3.4](www.anaconda.org)
2. [Scrapy](http://www.scrapy.org)
3. [MongoDB](https://www.mongodb.com/download-center?jmp=tutorials&_ga=2.178732068.1438313614.1499229675-1474069727.1499229675)

### Reference 

* [Scrapy_Official_Tutorial_Example](https://github.com/rh01/Scrapy_Official_Tutorial_Example)
* [scrapy official tutorials](https://doc.scrapy.org/en/latest/intro/tutorial.html)
* [scrapy tutorial videos](https://www.youtube.com/watch?v=LRFSNPVsOD0&list=PLlOGeDt-ISLoiX7OyMHYT9t0DOUhL-pxi)

## How To Use

```shell
$ # start crawl zhihu.com
$ scrapy crawl zhihu
```

and you can see  results below.

![](http://olrs8j04a.bkt.clouddn.com/17-7-6/70872256.jpg)

and open Mongo Client, and you can see that.

![](http://olrs8j04a.bkt.clouddn.com/17-7-6/30154089.jpg)

## License

![](https://img.shields.io/packagist/l/doctrine/orm.svg)

