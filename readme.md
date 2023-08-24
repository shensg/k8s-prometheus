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
