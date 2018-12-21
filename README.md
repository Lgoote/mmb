# mmb 项目开发指南

在开发之前一定要仔细阅读该文档，该文档会实时更新组员最新的开发情况。<br>
建议各组员watching该项目，以便项目更新后会第一时间通知你

<br>
<br>

## 目录及文件说明

MMBApiServer：服务器后端代码<br>
docs：说明文档目录<br>
mmb-demo：mmb演示版本<br>
mmv-dev：mmb开发版本<br>
mongodb：mongodb数据库文件<br>
mongodb/*.json：数据库文件<br>
<br>
<br>

## CHANGELOG

### 2018-12-21 03:29
1. 已经更新所有api未公网ip，ip地址为：`**http://58.218.199.45:14985**` ，不推荐大家用内网api进行开发。<br>
2. 已经更新[后端API文档](docs/api.md) 以及[协作开发文档](COOPERATION.md) 和 [启动项目文档](docs/start.md)。<br>
3. 初始化[wiki](https://github.com/Yggdrasill-7C9/mmb/wiki)。
4. 仓库已经移除mongodb.exe（windows环境） 以及 node_modules 等依赖，需要自己独立开发后端的同学请自行安装。<br>
5. 关于开发中遇到的bug以及解决bug的思路会记录在 `docs/fixed.md` 文件内。<br>
6. 最后一次团队项目了，大家加油！
<br>
<br>

### 2018-12-21 12:18
1. 项目架构搭建完成
2. 更新mui框架为最新版
<br>
<br>

###  2018-12-21 13:10
1. 新增加项目[项目职责文档](docs/structure.md)，
<br>
<br>

## TODO

* [x] 修改mmb-dev为线上环境<br>
* [ ] 修改`coordination.md`文件中的json格式<br>
* [x] 添加公共样式文件以及公共js文件<br>
