# crius-cli
A Tooling for React.js Development

#### usage

1. `npm i -g crius-cli`
2. `c2 init projectname` 生成项目目录
3. 配置文件 `package.json` 信息，可修改
3. `npm install` 安装项目依赖
4. `npm run dll` 生成第三方依赖库
5. `npm run dev` 启动本地服务
6. `npm run build` 打包上线所需文件
7. `npm run upload` 静态资源上传至测试服务器

#### 参数说明

字段名 | 备注
---|---
name | 项目名称
version | 项目版本号
description | 项目描述
main | 入口文件
publicPath | 静态资源目录
ftpServer | 静态文件服务器
ftpTarget | 静态文件目录
previewDir | 项目浏览服务器
author | 作者信息
