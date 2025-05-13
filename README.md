#### docker常用命令

根据dockerfile创建镜像
```bash

Docker builds build -t {image_name} .

```

创建docker容器

```bash

docker run ...
```

查看容器启动失败原因
```bash

docker logs  {pod_id}
```

进入容器
```bash

docker exec 
```

启动、停止、重启容器
```bash

docker start、stop、restart
```

#### docker-compose.yml的使用