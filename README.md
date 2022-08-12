> # 注意事项
>
> ```bash
> docker-compose-build.yml使用的dockerfile进行构建镜像，启动失败
> 
> docker-compose.yml使用的是dockerhub/wojiushixiaobai提供的镜像，启动成功
> ```





## Jumpserver Docker-Compose

```
$ git clone https://github.com/jumpserver/Dockerfile.git
$ cd Dockerfile
$ cat .env
$ docker-compose up
```

build
```
$ cd docker-compose
$ cat .env
$ docker-compose -f docker-compose-build.yml up
```
## 说明

- .env 的变量 用在 docker-compose 里面, 可以自己看下
可能还有一些未能检测到的问题, 尽量自己调试一遍后再使用

> 如果自己编译, 可以在 docker-compose 的 environment: 处加入 Version: $Version , 取代 Dockerfile 的 ARG



# docker-compose文件说明

 <font color=red>`docker-compose.yml `使用的是wojiushixiaobai提供的镜像</font>

 <font color=red>`docker-compose-build.yml` 使用的是官方镜像</font>

