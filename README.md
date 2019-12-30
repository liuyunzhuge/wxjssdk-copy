# wxjssdk-copy
可用于npm的wxjssdk版本。代码直接从官方copy过来，方便项目中通过构建工具使用。不知道官方为啥不自己发布一个npm包...

阅读官方使用说明：[wxjssdk](https://developers.weixin.qq.com/doc/offiaccount/OA_Web_Apps/JS-SDK.html); [微信 JS 接口签名校验工具](https://mp.weixin.qq.com/debug/cgi-bin/sandbox?t=jsapisign)

## 使用
安装
```
npm install wxjssdk-copy --save
```
使用：
```js
import wx from 'wxjssdk-copy'

// use wxjssdk with `wx` variable
```

目前此库同步的是官方[1.4.0的版本](https://res.wx.qq.com/open/js/jweixin-1.4.0.js)。
