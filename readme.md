# 百度分享不支持Https的解决方案  #

### 如何修改获得该代码等详见Blog： ###
https://www.hrwhisper.me/baidu-share-not-support-https-solution/

### static/api/js/share.js做如下修改： ###
```
window._bd_share_main = {
    version: "2.0",
    jscfg: {
        domain: {
            //该字段是 加载 其他js文件的url前缀
            staticUrl: "https://hjzgg.github.io/baiduShare/"
        }
    }
}

```

