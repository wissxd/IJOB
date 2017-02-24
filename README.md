# IJOB
该项目是一个基于NodeJS，以科技生活资讯为分享内容的平台。
##技术选型:

    NodeJS ：基础核心开发语言

    Express：web应用框架

    MongoDB：文档型数据库（非关系型数据库）

##第三方模块&中间件：

    bodyParser：解析post请求数据

    cookies：   读／写cookie

    swig：      JS模板解析引擎

    mongoose：  建模工具（将MongoDB存储的文档转化为JS对象，然后可以直接进行数据的增删改查）


##项目结构

###目录结构：

    [db]           数据库存储目录

    [models]       数据库模型文件目录

    [node_modules] node第三方模块目录

    [public]       公共文件目录（css,js,image...）

    [routers]      路由文件目录

    [schemas]      数据库结构文件（schema）目录

    [views]        模板视图文件目录

    app.js         应用启动（入口）文件

    package.json   配置文件


###前台路由+模板

####main模块

    /             首页
    /view         内容页

####api模块

    /             首页
    /register     用户注册
    /login        用户登录
    /comment      评论获取
    /comment/post 评论提交


###后台路由+模板

####admin模块

    /                   首页
    用户管理
    /user               用户列表
    分类管理
    /category           分类列表
    /category/add       分类添加
    /category/edit      分类修改
    /category/delete    分类删除
    内容管理
    /content            内容列表
    /content/add        内容添加
    /content/edit       内容编辑
    /content/delete     内容删除
    评论管理
    /comment            评论列表
    /comment/delete     评论删除
