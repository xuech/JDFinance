# JDFinance
以京东金融为学习Vue组件思想的切入点

### 技术亮点
`组件化设计 ` + `css模块化`+`组件化的设计思想`

CSS模块化：

* 设计原则

    a、可复用能继承要完整
    b、周期性迭代

* 设计方法与思想：

    a、先整体后部分再颗粒
    b、先抽象再具体

JS组件设计：

* 设计原则
    a、高内聚低耦合
    b、周期性迭代

* 设计方法与思想：
    a、先整体后部分再颗粒
    b、尽可能抽象

自适应：

* 基本概念
    a、[css像素、设备像素、逻辑像素、设备像素比](https://github.com/jawil/blog/issues/21)
    b、viewpoit
    c、rem


* 工作原理
    a、利用viewpoit和设备像素比调整基准像素
    b、利用px2rem自动转换css单位

### 技术应用
*  开发环境:
    Node
*  开发工具:
    Visual Studio
*  构建工具:
    webpack
*  基础技术框架:
    vue + vue-router + sass
*  应用插件:
    vue-awesome-swiper
*  页面自适应:
    rem + hotcss
*  代码格式化:
    eslint + vue-style-loader
* 版本控制器:
    git
    
###  文件app目录
```
├── css  //css抽象
│   ├── element.scss
│   ├── layout.scss
│   └── reset.scss
│
├── js	
│    ├── core  //核心组件
│        ├── btn.vue     //按钮
│        ├── panel.vue   //面板
│        └── slider.vue  //轮播图
│    ├── home    //首页组件
│    ├── ious    //白条组件
│    ├── money   //理财组件
│    ├── public  //公共组件 
│    ├── raise   //众筹组件
│    ├── router  
│        └── index.js //路由配置
│    ├── App.vue
│    ├── main.js      //入口文件
│    ├── package.json //包依赖文件
│    └── viewport.js  //px2rem
│    
└── views	//视图
    └── index.html
    
```

