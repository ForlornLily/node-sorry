# node-sorry

`sorry有钱真的可以为所欲为`

## 说明

分支将html模板更改为ejs；核心内容尚未探索。

思路参考[sorry](https://github.com/xtyxtyx/sorry)
目前已有
[Ruby](https://github.com/xtyxtyx/sorry)
[Python](https://github.com/East196/sorrypy)
[Java](https://github.com/li24361/sorryJava)


node-sorry 使用的技术栈：
- 1、nodejs 8.1 + express 4 + ejs
- 2、Express Generator



## 目录结构

```
├─bin
│  │
│  └─www                     //是应用的主入口
│
├─controller                 // 后端Contoller
│  │  
│  └─render.js               // 核心代码，用ffmpeg生成gif图
│ 
├─node_modules               // 依赖
│
├─public                     // 静态资源
│  │
│  ├─cache                   //gif输出目录
│  │
│  ├─images                  //图片
│  │
│  ├─javascripts             //js
│  │
│  ├─stylesheets             //css样式
│  │
│  └─templates               //gif模板
│
├─routes                     // 路由目录
│  │
│  └─index.js                // 路由文件
│
├─views                      // 视图模板
│  │
│  ├─header.ejs              //公用部分 
│  │
│  ├─footer.ejs              //公用部分
│  │
│  ├─xxx.ejs                 // sorry等输入框部分的内容
│  │
│  └─404.ejs                 // 404页面
│
├─app.js                     // 主要配置文件
│
├─ffmpeg.exe                 // 方便window用户使用，linux请安装
│
└─pageage.json
   
   
```



## 准备工作:
安装 NodeJS（请按照node8以上）:
https://nodejs.org/zh-cn/


## 部署
```shell
# 安装依赖
$ npm install

# 启动
$ npm run start
```
浏览器打开[http://localhost:3000/](http://localhost:3000/)

其余部分见主分支~https://github.com/q809198545/node-sorry

## Node.js入门踩坑（0基础）：
<ul>
<li>书籍<a href="https://www.amazon.cn/dp/B00ALPRM3W/ref=sr_1_6?ie=UTF8&qid=1522147601&sr=8-6&keywords=nodejs" title="Node.js开发指南">Node.js开发指南</a> by 郭家宝(BYVoid)</li>
<li><a href="https://yunnysunny.gitbooks.io/nodebook/content/" title="台湾nodejs社区翻译">Node.js Wiki Book简体版</a></li>
<li><a href="https://yunnysunny.gitbooks.io/nodebook/content/" title="台湾nodejs社区翻译">《一起学 Node.js》</a></li>
</ul>
