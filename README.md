# v2ray-docker

### 安装 docker 和 docker-compose
```
curl -fsSL https://get.docker.com | bash

curl -L "https://github.com/docker/compose/releases/download/1.25.3/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

chmod a+x /usr/local/bin/docker-compose
```

### Clone docker 和配置文件
```
git clone https://github.com/online2311/v2ray-docker.git

cd v2ray-docker

# 配置
修改 config.json 中的 poseidon 下面的 nodeId, webapi, 和 token

# 启动
docker-compose up -d
```
