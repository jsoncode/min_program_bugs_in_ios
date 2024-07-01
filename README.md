# min_program_bugs_in_ios
Mini Program Bug in iOS Devices ios中的微信小程序bug汇总

一下搜集了ios端微信小程序的各种bug

来自网友反馈，未验证，自行验证

## 不支持encodeURIComponent

https://developers.weixin.qq.com/community/develop/doc/000e6cadfe89d84ae2d86fbf456800

## new Date('')兼容性

https://www.finclip.com/news/f/14898.html

```
// 错误示例，不支持横杠
new Date('2024-07-01')

// 正确实例
new Date('2024/07/01')
```


## wx.getSystemInfoSync获取windowHeight不准确

## 不支持图片路径大写src='imgs/iphoneBGT.png'

## storage里的空值判断非常规

https://blog.csdn.net/qq_51534884/article/details/123672336

## ios不允许(?<=、?<!、?!、?=)

https://developers.weixin.qq.com/community/develop/doc/000844758286a09a69b0de6206bc00
