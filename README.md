# kds

dgraph 取第一个字母，替换k8s 中的8.

kds 的目标是通过 dgraph 图数据库保存 k8s 中各个资源之间的依赖关系，同时使用 dgraph 提供的 web 界面将这种依赖关系图形化展示出来。

## 工具

go 1.16.6 

dgraph install:
    docker pull dgraph/standalone  (注意 OS 的不同)
    https://dgraph.io/docs/dgraph-overview/#to-run-dgraph-using-the-standalone-docker-image
    https://dgraph.io/docs/dgraph-overview/#get-started-with-self-managed-dgraph

    启动：
         ``` docker run -it -p 5080:5080 -p 6080:6080 -p 8080:8080 -p 9080:9080 -p 8000:8000 -v ~/dgraph:/dgraph --name dgraph dgraph/standalone:v21.03.0```


docker 20.10.7

kubernetes 

## Tip

docker 启动 dgraph

https://dgraph.io/docs/deploy/download/

