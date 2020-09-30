# drozer

感谢开源精神，我将根据自己的使用需要进行一些定向修改。

## 更改点
- app.activity.info

更了filter参数改后，使用命令：
```
dz> run app.activity.info -f "WbShareTransActivity,WbShareToStoryActivity"

输出展示参考如下：
Package: my.maya.android
[-----------------------Hidden Activities:-------------------------]
    com.sina.weibo.sdk.share.WbShareTransActivity
      Permission: null

[-----------------------Hidden Activities:-------------------------]
    com.sina.weibo.sdk.share.WbShareToStoryActivity
      Permission: null

Package: com.lemon.faceu
[-----------------------Exported Activities:-----------------------]
    com.sina.weibo.sdk.share.WbShareTransActivity
      Permission: null

[-----------------------Exported Activities:-----------------------]
    com.sina.weibo.sdk.share.WbShareToStoryActivity
      Permission: null
```
