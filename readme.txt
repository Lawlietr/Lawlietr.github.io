1.
DNS1:104.199.253.96
https://adh.avpclub.gq/dns-query
tls://adh.avpclub.gq

基於 AdGuard Home 服務
The service it's based on the AdGuard Home

本服務收到的 DNS 請求，會全部返回上游 tls://1dot1dot1dot1.cloudflare-dns.com
All receive of the dns query requests will forward to the tls://1dot1dot1dot1.cloudflare-dns.com

目前已不再紀錄任何 DNS 查詢結果
The service will not record any dns query now

2.
 支援 DNS over HTTPS, DNS over TLS, 使用 adh.avpclub.gq
Support both of DNS encryption, (DNS over HTTPS, DNS over TLS)

3.
目前使用的過濾器規則:
How many filters are used:

AdGuard Simplified Domain Names filter
https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt

https://1hos.cf/mini/

https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts

https://raw.githubusercontent.com/vokins/yhosts/master/hosts

https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext

https://gitlab.com/ZeroDot1/CoinBlockerLists/raw/master/hosts_browser


4.
自建黑白名單:
How many rules created by me

#below it is whitelist
@@||1hosts.cf^
@@||adaway.org^
@@||b-api.facebook.com^
@@||cdn.taboola.com^
@@||click.simba.taobao.com^
@@||count.taobao.com^
@@||dailyupdate.wangwang.taobao.com^
@@||ebc.net.tw^
@@||filters.adtidy.org^
@@||graph.facebook.com^
@@||h-adashx.ut.taobao.com^
@@||hosts-file.net^
@@||i.click.taobao.com^
@@||ju.taobao.com^
@@||m.taobao.com^
@@||mirror1.malwaredomains.com^
@@||mmstat.com^
@@||mos.m.taobao.com^
@@||mqtt-mini.facebook.com^
@@||mtop.subaru.pc.mini.detail^
@@||news.ebc.net.tw^
@@||passport.baidu.com^
@@||pgl.yoyo.org^
@@||raw.githubusercontent.com^
@@||s.click.taobao.com^
@@||s3.amazonaws.com^
@@||sysctl.org^
@@||tui.taobao.com^
@@||winhelp2002.mvps.org^
@@||world.taobao.com^
@@||zeustracker.abuse.ch^
@@||api.io.mi.com^
@@||data.mistat.xiaomi.com^
#
# below it is blacklist
||ads.ad2iction.com^
||ads.flurry.com^
||aotter.net^
||apnsgcm.superweather.tw^
||apnsgcmt.superweather.tw^
||atsv2-fp.wg1.b.yahoo.com^
||image.superweather.tw^
||moptt.azurewebsites.net^
||moptt.blob.core.windows.net^
||tkmftc.aotter.net^
