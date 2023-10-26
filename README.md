## 微信小程序 - 便利店在哪

一个帮你快速找到附近便利店的小程序。

## 功能

- [x] 实时显示附近的便利店
- [x] 点击图标获取便利店信息
- [x] 显示当前所在地与天气状况

## 概览

![](https://raw.githubusercontent.com/royeo/static/master/img/weapp-store.jpeg)

## 小程序码

![](https://raw.githubusercontent.com/royeo/static/master/img/weapp-store-qrcode.jpg)

## 运行

在 [高德地图开放平台](https://console.amap.com/dev/key/app) 申请 key，将申请到的 key 替换 `pages/index/index.js` 中的 key，即可搜索到附近的便利店。

```js
const AMap = new amap.AMapWX({key:'xxxxxx'});
```
