# lowcode-cms
基于dooring低代码社区的开源cms系统

<img src="./lowcode.png" width="100%" />

线上体验地址: http://www.lowcoder.cn/

## 系统架构

<img src="./lld.png" width="100%" />

### 目录介绍

- server 基于nodejs的服务端, 启动后可直接访问`3000` 端口, 也就是内容SSR端
- admin CMS的管理后台, 集成了用户管理, 内容审核, 内容发布, 数据统计等模块

开箱即用~~

### 本地启动

1. server端

```
# 进入server目录
cd server
# 安装依赖
yarn
# 服务端启动
yarn start
```

注: 如果是window系统, 可以执行 `yarn start:win`

2. 管理端

```
# 进入admin目录
cd admin
# 安装依赖
yarn
# 启动
yarn start
```

初始化账号: `super_123`, 密码: `zxzk_123`

3. 内容端

访问`3000`端口即可.


