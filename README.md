# baiduwp
PanDownload Web, built with CloudFlare Workers
# Demo
No longer available due to abuse.
# Usage
```
headers:{
    'user-agent': 'Some UA',
    'Cookie': 'BDUSS=INPUT YOUR BDUSS HERE; STOKEN=INPUT YOUR STOKEN HERE'
  }
```
需要Cloudflare的Workers
复制代码粘贴到编辑器
使用查找替换找到如下内容并替换
**INPUT YOUR BDUSS HERE**
**INPUT YOUR STOKEN HERE**
顾名思义，就是替换成SVIP账号的cookie等信息，建议找一个共享号的。
先登录SVIP的网页版百度云，chrome可以使用插件EditThisCookie很方便找到相应内容。
</br>
![](https://ftp.bmp.ovh/imgs/2020/08/a8275c0f0fb1a5f2.png)
</br>
![](https://ftp.bmp.ovh/imgs/2020/08/9be1d79458845402.png)
</br>
找到Cloudflare的Workers，创建Workers。
复制替换好的代码
</br>
![](https://ftp.bmp.ovh/imgs/2020/08/ee8179b526f85b8c.png)
</br>
左侧粘贴代码，点击保存并部署，右侧就可以看到链接。
搭建完成
# Thanks

[PanDownload](https://pandownload.com): static pages

[KinhDown](https://t.me/kinhdown): client type

[PNL](https://www.lanzous.com/u/pnl): download method

[acgotaku/BaiduExporter](https://github.com/acgotaku/BaiduExporter): send to aria2
