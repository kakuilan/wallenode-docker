# wallenode-docker
wallenode-docker  
walle-web 包含nodejs,npm的打包镜像


#### 使用方法
```shell
#创建本地镜像
git clone https://github.com/kakuilan/wallenode-docker.git
cd wallenode-docker/
sudo docker build -t myimg .

#拉取网络镜像
sudo docker pull kakuilan/wallenode-docker:latest
```

#### nodejs版本
- node  10.16.3
- npm   6.10.3
- yarn  1.17.0
- npx   6.10.3

#### 挂载目录
- /opt/walle_home/codebase
- /opt/walle_home/logs
- /opt/walle_home/node_module/npm_cache
- /opt/walle_home/node_module/npm_global
- /opt/walle_home/plugins
