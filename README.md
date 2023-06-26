# 运行

## 安装依赖

npm install
**必须使用 npm 不然打包会报错**

## 清除依赖

rmdir /s node_modules

## Web 端运行

pnpm dev

## Web 打包

pnpm build:pro

## electron 运行

pnpm electron:dev

pnpm electron:prop
**运行生产前必须先打包 web**

## 打包 electron

npx electron-forge import
