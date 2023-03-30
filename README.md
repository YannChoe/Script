#!name=微信公众号去广告
#!desc=去除微信公众号广告
## 去微信公众号广告
[Script]
http-response ^https?:\/\/mp\.weixin\.qq\.com\/mp\/getappmsgad requires-body=1,max-size=0,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/File/Wechat.js

[MITM]
hostname = mp.weixin.qq.com
