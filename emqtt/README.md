# emqtt
部署时：
1、修改service及deployment名称
2、修改service的nodePort（若不需要对外暴露接口，则注释掉type: NodePort及所有的nodePort）
3、修改deployment的镜像启动环境变量。参见[https://github.com/emqtt/emq-docker]
