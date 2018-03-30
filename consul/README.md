# consul

部署时：
1、修改deployment的名称及端口（若不需要对外暴露接口，则不部署service）
4、修改consul实例数量：修改deployment的replicas及-bootstrap-expect为相同的值，推荐3-5.
