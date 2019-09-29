# lirener.github.io
自身cname文本到自己域名[btsync.gq]

www.dnspod.com [btsync.gq] => cname 到 Cloudflare nameservers【2选1】 

www.dnspod.com [btsync.gq] => url =www.重定向到自身[btsync.gq]

www.cloudflare.com [btsync.gq] [云)=> cname 到 lirener.github.io

www.cloudflare.com [btsync.gq] => cname 到 url.dnspod.com 

域名注册商-设置 NS NAME server

添加 腾讯dnspod国际解析 3个

添加 cloudflare云解析 2个

成功都设置完毕后
自定义域名查询[119.29.29.29=腾讯DNS][8.8.8.8=谷歌DNS]：

nslookup btsync.gq 8.8.8.8

nslookup www.btsync.gq 8.8.8.8
