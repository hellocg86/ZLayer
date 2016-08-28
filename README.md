#ZLayer Android企业级应用开发框架 （直播代码版）#

###项目分层###
    核心基础服务层，业务抽象层，业务层
    （当业务需求较大的时候，可以将三层水平架构进行纵向切分，使用组件化架构）

###说明###
Android的基础服务层，旨在将精力花在应用逻辑和交互上的开发，
      缩短开发周期。

###服务说明###
    MVP架构:实现mvp架构的基类
    
###网络请求###
封装retrofit实现，抽离出网络请求层
      (1) 设置统一header
      (2) 支持https
      (3) 控制缓存
      (4) 开关log
      (5) 设置超时
      (6) 在服务层处理服务端状态码
      (7) 实现接口联调
      (8) 支持基本数据类型，ConcurrentHashMap，RequestBody传递参数
      (9) 文件上传，下载，进度条监听

###图片加载###
支持切换各种流行图片加载库，默认装载glide
    
###常用工具类###
日志，toast，时间，设备，加密，json to pjop，bitmap，数学，包，字符串，view，文件，动画
    
  
    
