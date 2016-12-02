# 多云引擎应用负载均衡示例

## 目的

一些请求量很大的应用可能会采用多个云引擎示例组合完成整体的 web 服务。请求先经过 gateway，根据 url path 路由到具体的 backend 进行处理。每个 backend 相对独立，资源控制能力和整个 web 服务容量会有很大的提升。
