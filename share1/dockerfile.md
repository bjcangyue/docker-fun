## Dockerfile 使用说明
>
    Dockerfile 是 docker 用来构建镜像的文件
    
### 官方 `Dockerfile` 说明
>
    https://docs.docker.com/engine/reference/builder/
    
### 使用 `Dockerfile` 构建镜像

`docker build -t $IMAGE_NAME $DOCKERFILE_PATH`

* 例如: `docker build -t nginx_test .`