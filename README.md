# JK的附件表
<div style="text-align:center;">
    <img width="256" src="./img/Docker.png" alt="Docker Image">
</div>

### Docker安装
#### 安装 yum-utils 工具
```
yum install yum-utils
```
#### 要将阿里云的 Docker CE 镜像源添加到 CentOS 7 的 yum 配置中
```
yum-config-manager --add-repo http://mirrors.aliyun.com/docker-ce/linux/centos/docker-ce.repo
```
#### 要在 CentOS 7 中安装 Docker CE
```
yum install -y docker-ce
```
#### 启动 Docker 服务
```
systemctl start docker
```
#### 系统启动时自动启动 Docker 服务
```
systemctl enable docker
```