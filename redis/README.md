# redis
文件*-cc.yaml表示redis集群控制阶段的service及statefulset部署文件
文件*-cluster.yaml表示redis集群节点的service及statefulset部署文件
文件*-nodeport.yaml表示对外暴露的接口的服务部署文件
部署时：
1、修改本部署文件内的服务名及statefulset、pod名称不可更改
2、修改*-nodeport.yaml的nodePort（若不需要对外暴露接口，不部署该文件）
