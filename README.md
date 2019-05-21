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
- node  10.15.3
- npm   6.4.1
- yarn  1.13.0
- npx   6.4.1
- cnpm  6.0.0