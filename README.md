# SS/SSR去广告规则
* 项目基于CC-BY-SA-4.0协议发布
* 仅推荐未root的安卓手机使用。
* Telegram频道订阅地址：**https://t.me/ACL4SSR**


# root手机推荐：
* 1.自带去广告的VIA浏览器 http://www.coolapk.com/apk/mark.via
* 2.HOSTS 广告快走中国版 http://www.coolapk.com/apk/mark.via
* 3.HOSTS 广告快走开AdAway http://www.coolapk.com/apk/org.adaway
* https://raw.githubusercontent.com/vokins/yhosts/master/hosts

# 版本解释
* banAD.acl （默认代理）去广告+局域网直连+国内IP段直连+国内常用域名直连+国外代理
* gfwlist-banAD.acl （默认直连）去广告+局域网直连+国外gfwlist列表代理
* onlybanAD.acl （默认代理）去广告+局域网直连+全局代理
* fullgfwlist.acl （默认直连）国外gfwlist列表代理，没有去广告，没有白名单（原版SS可直接复制文件内容使用）
* backcn-banAD.acl （默认直连）去广告+国内IP段代理+国内常用域名代理+局域网直连+国外直连
* nobanAD.acl （默认代理）局域网直连+国内IP段直连+国内常用域名直连+国外代理
* SSR C#规则 gfwlist-user.rule （默认直连）去广告+局域网直连+国外gfwlist列表代理

# 安卓 SS/SSR 去广告ACL规则
* 屏蔽小米手机和魅族flyme rom系统广告
* 国内网站均直接连接
* 屏蔽常用视频网站广告
* 屏蔽常用网站广告、其他流媒体网站广告
* 屏蔽部分应用程序开屏广告
* 屏蔽部分运营商劫持网页弹出的漂浮球广告、流量统计
* 拦截常用应用程序的隐私跟踪、行为分析、数据统计

# ♻️ SS/SSR ACL Files Download：
* ACL更新地址（**白名单**）：https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/banAD.acl
* ACL更新地址（**黑名单**）：https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/gfwlist-banAD.acl
* ACL更新地址（**全局**）：https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/onlybanAD.acl
* ACL更新地址（**仅GFWList**）：https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/fullgfwlist.acl
* ACL更新地址（**国内代理**）：https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/backcn-banAD.acl
* ACL更新地址（**白名单，无去广告**）：https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/nobanAD.acl
* SSR C# GFWList user.rule ：https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/gfwlist-user.rule


* SS：https://github.com/shadowsocks
* SSR-WIN：https://github.com/shadowsocksr/shadowsocksr-csharp/releases
* SSR-安卓：https://github.com/shadowsocksr/shadowsocksr-android/releases

# ♻️ Surge/Shadowrocket Config File Download：
* 请到相关项目页面根据说明配置 https://github.com/lhie1/Surge

📋 教程 / 说明：
* 打开SSR->路由->自定义acl文件->输入下载地址->更新
* 再次更新，点击软件页面底部的更新即可

# 注：
* 参照vokins大神的hosts规则改编，致谢!! https://github.com/vokins/yhosts
* 参照lhie1大神的surge规则改编，致谢!! https://github.com/lhie1/Surge
* 参照scomper大神的surge规则改编，致谢!!https://gist.github.com/scomper/915b04a974f9e11952babfd0bbb241a8/revisions

* 浏览器内部广告太多了，单凭几百条规则可能过滤不过来。少许遗漏，请谅解
* 有问题请发issue,说明状况和所用规则。
* temp文件夹为历史存档 要找以前的版本可以下那个
		
# License		
* CC-BY-SA-4.0
