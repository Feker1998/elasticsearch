# elasticsearch\
本实例采用的是elasticsearch-6.2.4版本，安装在服务区器\
#elasticsearch.yml重要参数:\
network.host: 0.0.0.0\
http.port: 9200\
cluster.name: feker\
network.publish_host: 101.200.124.173

#jvm.options(由于我服务器比较小，所以java堆小一些)\
-Xms512m\
-Xmx512m

另外，推荐一个es安装的教程\
https://www.imooc.com/article/254644

如果在程序启动的过程中出现报错，则直接百度