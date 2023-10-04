# clash-template

### clash 订阅转换模板
https://raw.githubusercontent.com/this-cat/clash-template/main/template.ini

### clash 自定义规则
```yaml
# steam
- DOMAIN-SUFFIX,cdn-ali.content.steamchina.com,DIRECT
- DOMAIN-SUFFIX,lv.queniujq.cn,DIRECT
- DOMAIN-SUFFIX,xz.pphimalayanrt.com,DIRECT
- DOMAIN-SUFFIX,dl.steam.clngaa.com,DIRECT
- DOMAIN-SUFFIX,steamcontent.com,DIRECT
- DOMAIN-SUFFIX,steamstatic.com,DIRECT
- DOMAIN-SUFFIX,steamserver.net,DIRECT
- DOMAIN-SUFFIX,test.steampowered.com,DIRECT
- DOMAIN-SUFFIX,store.steampowered.com,Proxy
- DOMAIN-SUFFIX,api.steampowered.com,Proxy
- DOMAIN-SUFFIX,rmbgame.net,DIRECT

# microsoft
- DOMAIN-SUFFIX,time.windows.com,DIRECT
- DOMAIN-SUFFIX,windows.com,DIRECT
#- DOMAIN-SUFFIX,cn.bing.com,DIRECT
#- DOMAIN-SUFFIX,s.cn.bing.net,DIRECT
#- DOMAIN-SUFFIX,r.bing.com,Proxy
#- DOMAIN-SUFFIX,www.bing.com,Proxy
#- DOMAIN-SUFFIX,bing.com,Proxy
- DOMAIN,onedrive.live.com,Proxy
- DOMAIN-SUFFIX,outlook.live.com,DIRECT
- DOMAIN-SUFFIX,live.com,DIRECT
- DOMAIN-SUFFIX,microsoft.com,DIRECT
- DOMAIN-SUFFIX,microsoftonline.com,DIRECT
- DOMAIN-SUFFIX,office365.com,DIRECT
- DOMAIN-SUFFIX,events.data.microsoft.com,DIRECT
- DOMAIN,nleditor.osi.office.net,DIRECT
- DOMAIN,msedge.b.tlu.dl.delivery.mp.microsoft.com,DIRECT
- DOMAIN,img-prod-cms-rt-microsoft-com.akamaized.net,DIRECT

# epic
- DOMAIN,download.epicgames.com,DIRECT
- DOMAIN-SUFFIX,ol.epicgames.com,DIRECT
- DOMAIN-SUFFIX,epicgames.dev,DIRECT

# meituan
- DOMAIN-SUFFIX,meituan.com,DIRECT

# npm
- DOMAIN,registry.npmjs.org,DIRECT

# docker
#- DOMAIN-SUFFIX,docker.com,DIRECT

# google
- DOMAIN,services.googleapis.cn,DIRECT
#- DOMAIN-SUFFIX,googleapis.cn,Proxy
- DOMAIN-SUFFIX,googleapis.com,Proxy
- DOMAIN-SUFFIX,xn--ngstr-lra8j.com,DIRECT
- DOMAIN-SUFFIX,googleusercontent.com,Proxy
#- DOMAIN,connectivitycheck.gstatic.com,Proxy

# blackarch
- DOMAIN-SUFFIX,blackarch.org,DIRECT
- DOMAIN,ftp.halifax.rwth-aachen.de,DIRECT

# openai
#- DOMAIN-SUFFIX,chat.openai.com,Proxy
#- DOMAIN-SUFFIX,openai.com,Proxy
#- DOMAIN,o33249.ingest.sentry.io,Proxy
#- DOMAIN,events.statsigapi.net,Proxy
#- DOMAIN,featuregates.org,Proxy
#- DOMAIN,widget.intercom.io,Proxy
#- DOMAIN,api-iam.intercom.io,Proxy

# paypal
- DOMAIN-SUFFIX,paypal.com,DIRECT

# allkeyshop
- DOMAIN-SUFFIX,allkeyshop.com,Proxy

# otr
- DOMAIN-SUFFIX,giftminer.net,Proxy
- DOMAIN-SUFFIX,keysforgames.co.uk,Proxy
- DOMAIN,neatdns.ustclug.org,Proxy
- DOMAIN-SUFFIX,yuanshen.com,DIRECT
- DOMAIN-SUFFIX,xtbw.shop,DIRECT
- DOMAIN-SUFFIX,fast.com,Proxy
- DOMAIN-SUFFIX,speedof.me,Proxy
- DOMAIN-SUFFIX,testmyspeed.onl,Proxy
- DOMAIN-SUFFIX,qbittorrent.org,DIRECT
- DOMAIN-SUFFIX,utorrent.com,DIRECT
```

```python
...
```
