# PROJECT OPENWRT
## A simple, fast, security DDNS client, powered by Oxygen233.
### Origin Blog link: https://233.ro/archives/233DDNS.html

### Welcome to my Telegram Group: [@ctcgfw\_openwrt\_discuss](https://t.me/ctcgfw\_openwrt\_discuss).
- - -
# Instructions for use
![Image text](https://raw.githubusercontent.com/project-openwrt/luci-app-233ddns/master/view.png)
### Dependencies: `busybox`, `coreutils-sha512sum`, `curl`.
### Simply select "Enable" and apply the configure, now you have a ddns domain for you.
- Please **keep your token secret**, or anyone can change your DDNS record anytime.
- The default update frequency is every minute, and you can find the command in the "Scheduled Tasks".
- You can only add a record that direct to IPv4 or IPv6.<br/>
Once you pushed your record to remote, you can never change your record from one into another.
- Token is randomly generated, you can change it anytime.<br/>
But please attention once you changed it, the subdomain will be changed simultaneously.
