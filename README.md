## Quick Start
```
// 升级node
npm install -g n
n stable

// 安装hexo
npm install -g hexo

// clone项目，注意该项目下包含子模块
git clone --recursive  https://github.com/IcefireCgrbza/IcefireCgrbza.github.io

// npm install
cd themes/icarus
npm install

cd ../..
npm install

// 本地启动
hexo server

// 发布
hexo generate
hexo deploy

// 新建页面
hexo new "xxx"
```