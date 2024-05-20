# clash-template

## 注意
只支持 clash.meta

## 依赖
GeoIP GeoSite

## 订阅转换模板
https://raw.githubusercontent.com/this-cat/clash-template/main/template.ini

## 自定义规则
```yaml
# gstatic
# steam
- DOMAIN-SUFFIX,s.team,Proxy
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
- DOMAIN-SUFFIX,steampowered.com,Proxy
- DOMAIN-SUFFIX,rmbgame.net,DIRECT
- DOMAIN-SUFFIX,steamcommunity.com,Proxy
- DOMAIN-SUFFIX,steamgames.com,Proxy

# microsoft
- DOMAIN-SUFFIX,time.windows.com,DIRECT
- DOMAIN-SUFFIX,windows.com,DIRECT
#- DOMAIN-KEYWORD,bing,Proxy
#- DOMAIN,www2.bing.com,Proxy
#- DOMAIN,www3.bing.com,Proxy
#- DOMAIN,www4.bing.com,Proxy
#- DOMAIN,th.bing.comProxy
#- DOMAIN,c.bing.com,Proxy
#- DOMAIN-SUFFIX,cn.bing.com,DIRECT
#- DOMAIN-SUFFIX,s.cn.bing.net,DIRECT
#- DOMAIN-SUFFIX,r.bing.com,Proxy
#- DOMAIN-SUFFIX,www.bing.com,Proxy
#- DOMAIN-SUFFIX,bing.com,Proxy
#- DOMAIN,r.msftstatic.com,Proxy
#- DOMAIN,sb.scorecardresearch.com,Proxy
#- DOMAIN,c.msn.com,Proxy
#- DOMAIN,assets.msn.com,Proxy
#- DOMAIN,api.msn.com,Proxy
#- DOMAIN-SUFFIX,outlook.live.com,DIRECT
#- DOMAIN,onedrive.live.com,Proxy
#- DOMAIN,storage.live.com,DIRECT
#- DOMAIN-SUFFIX,live.com,DIRECT
#- DOMAIN-SUFFIX,edge.microsoft.com,Proxy
#- DOMAIN-SUFFIX,microsoft.com,DIRECT
#- DOMAIN,login.microsoftonline.com,DIRECT
#- DOMAIN-SUFFIX,microsoftonline.com,DIRECT
#- DOMAIN-SUFFIX,office365.com,DIRECT
#- DOMAIN-SUFFIX,events.data.microsoft.com,DIRECT
#- DOMAIN,api-edge.cognitive.microsofttranslator.com,Proxy
#- DOMAIN,nleditor.osi.office.net,DIRECT
#- DOMAIN,msedge.b.tlu.dl.delivery.mp.microsoft.com,DIRECT
#- DOMAIN,img-prod-cms-rt-microsoft-com.akamaized.net,DIRECT

# epic
- DOMAIN,download.epicgames.com,DIRECT
- DOMAIN-SUFFIX,ol.epicgames.com,DIRECT
- DOMAIN-SUFFIX,epicgames.dev,DIRECT

# meituan
- DOMAIN-SUFFIX,meituan.com,DIRECT

# npm
- DOMAIN,registry.npmjs.org,Proxy

# docker
#- DOMAIN-SUFFIX,docker.com,DIRECT

# google
- DOMAIN-SUFFIX,dl.google.com,Proxy
- DOMAIN-SUFFIX,googleapis.cn,DIRECT
- DOMAIN-SUFFIX,googleapis.com,Proxy
- DOMAIN-SUFFIX,xn--ngstr-lra8j.com,DIRECT
- DOMAIN-SUFFIX,googleusercontent.com,Proxy

# googlevideo(YouTubeMusic)
#- DOMAIN-SUFFIX,googlevideo.com,Backup
#- IP-CIDR,173.194.0.0/16,Backup
#- IP-CIDR,172.217.0.0/16,Backup
#- IP-CIDR,74.125.0.0/16,Backup

# blackarch
- DOMAIN-SUFFIX,blackarch.org,DIRECT
- DOMAIN,ftp.halifax.rwth-aachen.de,DIRECT

# openai
- DOMAIN-SUFFIX,chat.openai.com,OpenAI
- DOMAIN-SUFFIX,openai.com,OpenAI
- DOMAIN-SUFFIX,chatgpt.com,OpenAI
- DOMAIN,o33249.ingest.sentry.io,OpenAI
- DOMAIN,events.statsigapi.net,OpenAI
- DOMAIN,featuregates.org,OpenAI
- DOMAIN,widget.intercom.io,OpenAI
- DOMAIN,api-iam.intercom.io,OpenAI

# paypal
- DOMAIN-SUFFIX,paypal.com,DIRECT

# allkeyshop
- DOMAIN-SUFFIX,allkeyshop.com,Proxy

# otr
- DOMAIN-SUFFIX,docs.rs,Proxy
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
- DOMAIN-SUFFIX,mutefun.tv,DIRECT
- DOMAIN-SUFFIX,2kdm.com,DIRECT
- DOMAIN-SUFFIX,download-cdn.jetbrains.com,DIRECT
- DOMAIN-SUFFIX,archlinux.org,DIRECT
- DOMAIN-SUFFIX,v2rayssr.com,US
- DOMAIN-SUFFIX,cdn.onesignal.com,Proxy
- DOMAIN-SUFFIX,cdn.oaistatic.com,Proxy
- DOMAIN-SUFFIX,whoer.net,Proxy
- DOMAIN-SUFFIX,framer.com,Proxy
- DOMAIN-SUFFIX,framerstatic.com,Proxy
- DOMAIN-SUFFIX,framerusercontent.com,Proxy
- DOMAIN-KEYWORD,www.rakuendoll.jp,US
- DOMAIN-KEYWORD,m.kumadoll.com,US

# weixin
- DOMAIN-KEYWORD,weixin,DIRECT
- DOMAIN-SUFFIX,qqwry.api.skk.moe,DIRECT

# claude
#- DOMAIN-SUFFIX,claude.ai,Other
#- DOMAIN-SUFFIX,forms.hsforms.com,Other
#- DOMAIN-SUFFIX,forms-na1.hsforms.com,Other
#- DOMAIN-SUFFIX,fonts.gstatic.com,Other
#- DOMAIN-SUFFIX,www.anthropic.com,Other
#- DOMAIN-SUFFIX,anthropic.com,Other
#- DOMAIN-SUFFIX,js.hsforms.net,Other
```
