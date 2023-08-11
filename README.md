**pnpm包管理工具**

+ 1、特点：速度快、节约磁盘空间、支持 monorepo、安全性高。

+ 2、pnpm对比npm/yarn的优点：更快速的依赖下载、更高效的利用磁盘空间、更优秀的依赖管理。

**pnpm的安装和使用**

+ 1、准备

> Node环境(✔️) && npm环境（✔️）

+ 2、安装

```shell
npm install -g pnpm
```

> 查看版本信息

```shell
pnpm -v
```

+ 3、设置镜像源

> 获取当前配置的镜像地址

```shell
pnpm config get registry
```

> 设置新的镜像地址

```shell
pnpm config set registry https://registry.npm.taobao.org/
```

+ 4、常用命令对比

> 1、npm 命令

```shell
npm install 安装全部依赖

npm install (包名) 安装指定包

npm uninstall (包名) 移除指定包

npm run 脚本 运行脚本
```

> 2、yarn 命令

```shell
yarn install 安装全部依赖

pnpm add (包名) 安装指定包

yarn remove (包名) 移除指定包

yarn run 脚本 运行脚本
```

> 3、pnpm 命令

```shell
pnpm install 安装全部依赖

pnpm add (包名) 安装指定包

pnpm remove (包名) 移除指定包

pnpm run 脚本 运行脚本
```

**依赖检查工具 - depcheck**

+ 1、安装

```shell
npm install -g depcheck
```

+ 2、在项目中使用 Depcheck 检查依赖

```shell
depcheck
```

+ 3、安装缺失依赖

```shell
pnpm install [缺失的依赖]
```
