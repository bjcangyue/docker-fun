## docker-comopse 使用说明

### 安装
>
    https://docs.docker.com/compose/install/

### docker-compose 是容器的编排工具, 可以一次性将多个容器放在一个`docker-compose.yml`文件中运行/停止/删除

#### 运行方法, 在docker-compose.yml 文件的当前目录执行
>
    docker-compose $COMMAND [OPTIONS]
* 运行`docker-compose up -d`,`-d`是以 daemon 方式运行
* 停止`docker-compose stop`
* 删除`docker-compose rm -f`,`-f`强制删除
* 更多请参考 https://docs.docker.com/compose/gettingstarted/
