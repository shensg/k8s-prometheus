# kube-prometheus安装及PromQL使用手册

##### * 开源不易，希望对你有所帮助的话，帮忙点一下star
##### * 如果有什么使用疑问可以留issue，笔者看到会尽量帮忙解决的

## 安装

### 安装kube-prometheus
###### 安装包括以下内容的修改
1、修改prometheus RBAC鉴权

2、prometheus数据持久化

3、grafana dashboard持久化

4、搜集pod,node自定义的label


### 配置PrometheusAlert
###### 默认以钉钉为例
1、如何修改告警的模板

2、拦截发送到钉钉的告警信息到自定义的webhook


## PromQL使用
### 主要介绍PromQL基础查询
1、包括计算函数： rate,irate,sum,count,group_left,group_right...

2、以及计算符号: +,-,*,/,%

3、过滤条件常用的计算符号：==,!=,>,<,>=,<=

4、过滤条件使用正则表达式
