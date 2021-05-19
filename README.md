<p align="center">
  <img height="100px" src="./ghost.png" />
</p>

# [Ghost](https://github.com/TryGhost/Ghost)

Ghost 是一个开源的博客平台, 是WordPress 的一个挑战者。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署


[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-Ghost&branch=master)

### 配置

- `database__client`：数据连接方式
- `database__connection__host`：数据库地址
- `database__connection__port`：数据库端口
- `database__connection__user`：数据库用户名
- `database__connection__password`：数据库密码
- `database__connection__database`：数据库名
- `url`：网站url


### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- CFS：使用 CFS 持久化存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
