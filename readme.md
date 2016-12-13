# 加密货币开发语言统计分析

这是[《Nodejs开发加密货币》](https://github.com/imfly/bitcoin-on-nodejs) 入门部门实例程序。是一个基于gihub的Api进行二次开发的统计分析工具，Statistical Analysis of Cryptocurrency Development Languages -- SACDL

[在线试用](http://imfly.github.io/sacdl-project/)

## 功能

* 自定义搜索。可以代替github针对版本库的高级搜索，自定义搜索任何关键字（不限于加密货币）;
* 数据可视化。可以输出列表、柱状图、矩阵图等交互性视图，方便、直观;
* 扩展性能好。集成了d3.js，可以根据自己喜好，添加和定制任何视图样式;
...

## 开发

安装依赖包

```
git clone https://github.com/[YourName]/sacdl-project.git
cd sacdl-project
npm install
bower install
```

构建代码

```
gulp 
```

部署到 `gh-pages`

```
gulp deploy
```

