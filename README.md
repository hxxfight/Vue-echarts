# 可视化项目

本项目为前后端分离的数据可视化项目，目的是为了加深Vue和echarts的学习

**个人学习和练习项目**



## 启动步骤

```
1.后端文件夹koa_server
$ npm install / cnpm install
$ node app.js

2.前端项目
$ npm install / cnpm install
$ npm run serve 
```



## 技术栈使用

### 后端

- Koa2

- WebSocket

### 前端

- vue2   vue-cli   vuex vue-router
- echarts
- WebSocket
- Webpack



## 实现功能

- 实时时间显示
- 一键更换主题
- 结合vue和echarts完成了线型图，柱形图，饼图和地图等形式的数据可视化
- 单个图表的放大全屏功能
- 图表数据的自动滚动功能
- 不同数据的菜单切换
- 地图展示，点击相应省份切换省份地图，双击回到全国地图
- 利用监控窗口大小来改变文字和图例的尺寸进行分辨率自适应



## 展示效果

默认主题：亮白

![](images\默认主题：亮白.png)

更换主题：黑夜

![](images\更换主题：黑夜.png)

单个图表全屏显示

![](images\单个图表全屏显示.png)

切换省份地图显示

![](images\省份地图显示.PNG)

后端发送数据的提示效果

![](D:\Mycode\vision_code\images\后端.PNG)