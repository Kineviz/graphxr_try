## Run graphXR Try version
> Default password is tuke
### 1. Download docker-compose.yml

```
wget https://raw.githubusercontent.com/GraphXR/graphxr-docker/master/docker-compose.yml
```

### 2. Run docker-compose

```
docker-compose up -d
```

### 3. Open graphXR
Use latest Chrome/Edge open http://localhost:9000

#### GraphXR info:

Username: admin@graphxr.cn
Password: tuke
URL : http://localhost:9000

> You can change the password and admin email in docker-compose.yml

#### Neo4j info:

Username: neo4j
Password: tuke
Bolt Port: 7687
Host: neo4j  (Connect with GraphXR use neo4j or IP)
Browser URL: http://localhost:7474

> You can change the password in docker-compose.yml

### 4. Stop docker-compose

```
docker-compose  down
```