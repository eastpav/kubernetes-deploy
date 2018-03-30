# mysql
暂无集群方式
部署时：
1、修改pv的storage的类型及位置
2、修改pvc的storage的声明
3、修改service的名称及端口（若不需要对外暴露接口，则注释掉type: NodePort及nodePort）
4、修改deployment的环境变量
