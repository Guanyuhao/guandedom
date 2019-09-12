## 一、查看Linux系统发行版本
```
cat /etc/issue
cat /etc/redhat-release
```
## docker 
docker images
docker ps | -a
docker start containerID
docker run -itd -p 5210:80 -v D:\docker_web:/home/work --name llpweb nginx 
docker exec -it  containerID  /bin/bash   进入镜像环境
docker commit  容器 镜像名字:tag
docker save -o 文件.tar 镜像
docker cp 
Usage:  docker cp [OPTIONS] CONTAINER:SRC_PATH DEST_PATH|-
        docker cp [OPTIONS] SRC_PATH|- CONTAINER:DEST_PATH
