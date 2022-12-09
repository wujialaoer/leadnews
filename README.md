# leadnews

> H5 模拟 APP视频播放
> node12下开发

## 目录结构

```javascript
├─api               //数据请求接口、相关函数和基础配置
├─base              //基础UI组件
├─common            //通用样式、工具类函数和icon图标
├─components        //核心功能组件
├─router            //路由配置文件
└─store             //vuex状态管理文件
App.vue           //根组件
main.js           //入口文件
```

## 项目问题

- 目前的项目性能较差，优化空间非常多，所以项目开发完成后会对性能进行优化
- 搜索框的内容中不可带有空格如果带有空格，会导致搜索出的结果出现代码无法编译的问题
- 搜索框需要清空文本框后输入才可显示搜索提示词
- 播放器的播放功能在Safari浏览器不兼容，导致无法播放
- 项目中的video-list模块设计思路错误

（以上问题是本菜鸡发现但还未解决的问题，后期会进行处理）

# Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```
