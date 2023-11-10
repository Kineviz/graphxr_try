## GraphXR 离线安装
> 默认密码： tuke

### 1. 下载GraphXR、mongoDB、Docker-compose
把文件下载到同一个目录（例如GraphXR）下

```
mkdir graphXR && cd graphXR
```

下载GraphXR 镜像  
```
wget https://img.graphxr.cn/tuke/graphxr.tar.gz
```

下载 mongoDB 镜像 
```
wget https://img.graphxr.cn/tuke/mongo-4.0.28.tar.gz

```

下载 Docker-compose 配置文件
```
wget https://img.graphxr.cn/tuke/docker-compose.yaml
```

### 2. 加载镜像

```
docker load < graphxr.tar.gz
```

```
docker load < mongo-4.0.28.tar.gz
```

### 3. 运行 docker-compose

```
docker-compose up -d
```

### 4. 打开 graphXR
推荐使用最新版本的 Chrome/Edge 浏览器打开 http://localhost:8080

#### GraphXR 信息:

Username: admin@graphxr.cn
Password: tuke
URL : http://localhost:8080

>你可以修改 ADMIN_EMAIL（Username）和password 在  docker-compose.yml 文件中

### 5. 停止 docker-compose

```
docker-compose  down
```

### 6. 激活GraphXR 
下载license请求文件，并发送给我们 (info#kineviz.com), 我们会发送激活文件给你。