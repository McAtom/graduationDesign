# graduationDesign
毕业设计--基于微信小程序的在线免费小说的开发

##目录说明
```
api --- 提供后台接口
    |-client --- 暂无用处
    |-common --- loopback的公共模型
    |-server --- loopback的服务器模型
            |- boot --- 初始化执行脚本
            |- modle --- 所有定义的模型目录
            |- datasources.json --- 数据源定义文件
            |- middleware.json --- 中间件配置文件
            |- modle-config.json --- 模型定义文件
            |- server.js --- 主程序
reptile --- 所有的爬虫目录
        |- connectDB --- 连接数据库，操作数据库方法类
        |- tools --- 实用方法类
        |- networkReptile.js --- 爬虫主程序
        |- config.js --- 爬虫配置js
weixin --- 微信小程序目录
       |- assets --- 静态资源文件
       |- datas --- 静态数据
       |- images --- 图片资源文件
       |- page --- 所有微信小程序的页面
       |- util --- 工具类
       |- app.js --- 微信小程序入口文件
```

## 前端完成进度
1. 登录页面 --- done
2. 今日页面 --- 完成了静态页面，尚未写接口逻辑
3. 我的书单页面 --- 完成了静态页面，尚未写接口逻辑
4. 教务页面 --- 完成了静态页面，尚未写接口逻辑
5. 书单排行榜页面 --- 未开始

## 后端完成进度
1. 爬虫升级 --- done ，现在可以同时爬去百度贴吧和爱下电子书两个来源的小说
2. 排行榜的爬虫 --- 尚未完成
3. 新增排行榜的接口 --- 未开始
