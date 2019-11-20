> notice: 2019毕设作品，后续如无必要将不再做功能性更新。

<img src="./public/chartfun.png" width="200"></img>

> Make data reports by dragging and dropping :)

## 特性 / Features

* 通过 Excel 导入数据
* 可视化画布
* 图表、图片、文字、边框支持
* 可拖拽和缩放的组件
* 静态数据、GET接口支持
* 生成公开链接

## 截图 / Screenshot

![image-1](./screenshot/1.png)

![image-2](./screenshot/2.png)

![image-3](./screenshot/3.png)

## 开发 / Develop

### 前端部分：Vue.js

#### Project setup

```
npm install
```

#### Compiles and hot-reloads for development

```
npm run serve
```

#### Compiles and minifies for production

```
npm run build
```

### 后端部分：Node.js + Koa + MongoDB

准备工作：配置并运行 MongoDB 数据库，新建一个空数据库并命名为`chartfun`。无需手动配置表结构，它们会被自动创建。

#### Run web-service

```
node ./server/app.js
```



## 鸣谢 / Thanks

本项目使用了 Vue.js 及以下第三方库：

* [ElemeFE / element](https://github.com/ElemeFE/element)
* [ElemeFE / v-charts](https://github.com/ElemeFE/v-charts)
* [josdejong / jsoneditor](https://github.com/josdejong/jsoneditor)
* [SortableJS / Vue.Draggable](https://github.com/SortableJS/Vue.Draggable)
* [mauricius / vue-draggable-resizable](https://github.com/mauricius/vue-draggable-resizable)
* [kirillmurashov / vue-drag-resize](https://github.com/kirillmurashov/vue-drag-resize)
* [koajs / koa](https://github.com/koajs/koa)

## LICENSE

MIT


## 待修正问题


1 图层折叠不容易选择 删除没有快捷键 或者页面添加一个按钮进行删除。

2 支撑的可视化图形比较少 需要进行扩充  待丰富插件 https://github.com/swort177/DataV  ， https://github.com/swort177/iDataV

3 登陆部分不完善

4 图片上传部分有问题  不显示。此处在WINDOWS下面有问题，需要注意路径问题。

5 待扩充数据整理，清洗等，此处略过，使用接口进行，契合微服务。

6 带扩充数据库支撑部分，此处略过，使用接口进行，契合微服务。

7 最后添加边框图标后，其它图形就不能动态选择数据了，鼠标放上去不会显示数据。

8 在1920*1080分辨率下面，添加左边统计图形的时候，右边的图形默认最小的会自动回位。其它分辨率暂未发现可能也有

