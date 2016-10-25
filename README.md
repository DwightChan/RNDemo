> 这个Demo是作为ReactNative iOS的项目框架整理，希望能够统一以这种方式去构建RN项目


##### 一、项目结构说明：

项目的第三方库以npm工具管理，同时原生方面若要引入第三方库，最好使用CocoaPods管理  

**一级目录说明：**

node_modules: 存放依赖库的文件夹，由npm自动生成

component: 存放JS组件

core: 存放核心的工具类，如网络请求，数据存储，公共方法等

ios: 这个就是原生的iOS根目录文件夹

android: 原生的android根目录文件夹

resource: 资源文件夹，存放图片和音视频等资源

index.ios.js: iOS项目入口

index.android.js: android项目入口

---

#### 二、技术栈
开发工具：Sublime Text  
需要安装一些相关插件，具体网上搜索

要学习的技术：React、React Native、JS、CSS  

网络通讯：Fetch / Ajax

数据存储：AsyncStorage

页面布局：JSX + CSS

##### 三、统一规范

1. 项目目录结构如上统一
2. 视图JSX + CSS布局