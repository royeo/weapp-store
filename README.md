## 微信小程序 - 便利店在哪

一个帮你快速找到附近便利店的小程序。

![](http://ovu6j7kst.bkt.clouddn.com/20180712032132.png)

![](http://ovu6j7kst.bkt.clouddn.com/weapp.jpg)

## 运行 Demo

在 [百度地图开放平台](http://lbsyun.baidu.com/index.php?title=wxjsapi) 申请密钥 （ak），将申请到的 ak 替换 `pages/index/index.js` 中的 ak，即可搜索到附近的便利店。

```js
const BMap = new bmap.BMapWX({
  ak: 'xxxxxx'  // 百度地图的 AK
});
```