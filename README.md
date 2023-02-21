# Juejin-CMS

本项目是基于Strapi的CMS系统，对[thresh111/thresh111-JueJin_id9527 (github.com)](https://github.com/thresh111/thresh111-JueJin_id9527)数据进行管理。

### 后台管理员账号

```
账号: 9527@juejin.com
密码: Qq123456
```

## 准备工作

在项目开始前，您需要将本项目clone到您的电脑主机。

### 安装node和yarn

安装node 16.x以上的 node.js, 使用yarn进行包管理。

node 版本 16.x <= node <= 18.x, 推荐使用 18.13.0

yarn 安装参考 [安装 | Yarn 中文文档 (bootcss.com)](https://yarn.bootcss.com/docs/install/#windows-stable)

若已有符合要求的 node 版本，直接进行下一步。

### 安装依赖

在运行项目之前，您需要先安装依赖。使用 yarn 包管理器安装项目依赖：

```
yarn install
```

## 运行项目

安装依赖之后，您可以使用以下命令来启动项目：

#### `develop`

此模式能够对后台内容和插件进行管理，推荐在数据维护的时候使用，使用如下命令启动。

```
npm run develop
# or
yarn develop
```

#### `start`

此模式推荐在生产模式进行使用，此时您不能够改变插件和数据。需要注意的是，需要在使用`yarn build`命令后使用。

```
npm run start
# or
yarn start
```

#### `build`

在使用start命令前对当前项目进行打包。

```
npm run build
# or
yarn build
```
