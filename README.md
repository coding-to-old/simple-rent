# simple-rent

> spider-rent是一个开源的找租房软件，目标是找到更多真实的租房房源，让在外工作租房的人能够更加轻松的找到房源。

spider-rent的主要特点:
* 爬取豆瓣真实的转租贴，信息比较真实
* 使用地图找房
* 与豆瓣贴的数据延迟在一个小时左右

下面是架构设计-----------------------------------------------------分割线

架构图
![架构图](https://github.com/coding-to-old/simple-rent/blob/master/IMG/s-rent%20Design.jpg?raw=true)

技术说明:

* spider server
爬虫服务使用 java webmagic [http://webmagic.io/](http://webmagic.io/)

* DTS、API server
数据转化服务器与api服务器使用 java

* 智能识别数据
使用 keras 、TensorFlow
[https://keras.io/](https://keras.io/)
[https://www.tensorflow.org](https://www.tensorflow.org)

* db
使用 mongodb 与 mysql

