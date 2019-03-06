# 皮肤宝Web前端框架

> 本框架涉大量使用[ES2015](http://es6.ruanyifeng.com/#README)语法,如果你还没能掌握 ES2015，你得抓紧了!  
> 已默认使用flex布局,严禁修改公共样式,页面最外层样式推荐使用 .container 以保证移动端良好的适配性  
> 项目已实现移动端适配,CSS单位统一使用px 作为基础单位  
> 项目中所用到icon推荐使用框架提供svg用以显示  
> 
> 


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for test with minification
npm run test

# build for production with minification
npm run build

# one key build 
run build.sh

```
# 功能
- [x] hash缓存             
- [x] 体积优化             
- [x] 通讯封装           
- [x] 通讯加密           
- [x] 状态管理             
- [x] V/M分离         
- [x] 路由懒加载            
- [x] 全局样式控制          
- [x] less全局定义         
- [x] svg封装        
- [x] iconfont引用      
- [ ] 签权封装         
- [ ] api封装         
- [x] 移动端自适应     
- [x] 环境分离    
  
>  大组件时代请用组件化的思路去编写程序   

### 本框架涉及以下内容:
[WebPack](https://www.webpackjs.com/concepts/)  
[NPM](https://www.npmjs.com.cn/)  
[VUE](https://cn.vuejs.org/v2/guide/)  
[Vue Router](https://router.vuejs.org/zh/)  
[Vuex](https://vuex.vuejs.org/zh/guide/)  
[axios](https://www.npmjs.com/package/axios)  
[JSEncrypt](https://github.com/travist/jsencrypt)  
[Lodash](https://www.lodashjs.com/)  
[Mint-UI](http://mint-ui.github.io/#!/zh-cn)  
[LESS](http://lesscss.cn/)

#项目结构
```
.
├── build                                       // webpack配置文件
├── config                                      // 项目配置
├── dist                                        // 生产环境输出内容
├── node_modules                                // 各种依赖,三方扩展
├── src                                         // 源码目录
│   ├── api                                     // 网络请求接口集
│   ├── assets                                  // 静态资源
│   ├── components                              // 组件
│   │   ├── svg                                 // svg相关
│   │   │   ├── icons                           // svg图集
│   │   │   │     └── iconExample               // svg示例
│   │   │   └── iconBase                        // svg图基础
│   │   └── Example.js                          // 示例组件
│   ├── filter                                  // 过滤器
│   │   └── filter.js                           // 过滤器实例
│   ├── pages                                   // 页面
│   ├── router                                  // 路由
│   │   └── index.js                            // 路由配置
│   ├── store                                   // vuex的状态管理
│   │   ├── modules                             // 各页面状态
│   │   │   └── example.js                      // example页面状态
│   │   ├── store.js                            // 状态调度中心
│   │   └── store-config.js                     // 状态仓库配置
│   ├── style                                   // 样式库
│   │   └── common.less                         // less样式库
│   ├── utils                                   // 工具类
│   │   ├── cryptoCode.js                       // RSA加密函数
│   │   ├── http.js                             // 网络请求函数
│   ├── App.vue                                 // 页面入口文件
│   ├── main.js                                 // 程序入口文件，加载各种公共组件
├── index.html                                  // 入口html文件

```
 
