# registry-secret
该文件部署一个docker-registry的secret，用于拉取私有镜像库的认证。
效果同kubectl create secret docker-registry
部署时：
1、修改dockerconfigjson的值为`base64 -w 0 ~/.docker/config.json`的执行结果
