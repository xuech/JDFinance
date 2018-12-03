# JDFinance
以京东金融为学习Vue组件思想的切入点

### 技术亮点
`组件化设计 ` + `css模块化`+`组件化的设计思想`

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

