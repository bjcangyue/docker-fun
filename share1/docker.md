## docker 命令的使用

### 安装 https://docs.docker.com/docker-for-mac/

### 拉取/推送镜像

`docker pull/push $IMAGE_NAME`

### 如何使用`docker`快速创建一个`nginx`服务环境

`docker run --name nginx-demo -d -p 80:80 nginx`

### 绑定本地数据卷

`docker run --name nginx-demo -d -p 80:80 -v ./html:/usr/share/nginx/html nginx`

### 自定义配置文件

`docker run --name nginx-demo -d -p 80:80 -v ./nginx/nginx.conf:/etc/nginx/nginx.conf nginx`

### ssh 到容器中

`docker exec -it nginx-demo bash`

### 查看容器详细信息

`docker inspect $CONTAINER_ID/$CONTAINER_NAME`

### 查看日志

`docker logs -f $CONTAINER_ID/$CONTAINER_NAME`

#### docker run 命令官方说明 https://docs.docker.com/engine/reference/run/

