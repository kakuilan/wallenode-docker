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
sudo docker run --rm -it kakuilan/wallenode-docker:latest node -v
sudo docker run --rm -it kakuilan/wallenode-docker:latest npm -v
sudo docker run --rm -it kakuilan/wallenode-docker:latest npx -v
sudo docker run --rm -it kakuilan/wallenode-docker:latest yarn -v
```

#### nodejs版本
- node  12.16.1
- npm   6.13.4
- npx   6.13.4
- yarn  1.22.0

#### 挂载目录
- /opt/walle_home/codebase
- /opt/walle_home/logs
- /opt/walle_home/node_module/npm_cache
- /opt/walle_home/node_module/npm_global
- /opt/walle_home/plugins

#### 注意
- 编译打包请使用yarn,弃用npm