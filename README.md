# fscan-Intranet

# 简介
这是fscan的内网修改版。

## 修改版
 [正式版下载](https://github.com/shadow1ng/fscan)首先附上作者原作，为作者的开源精神和一个nice的作品点赞

fscan的web扫描功能调用了xray的poc，这个确实非常好用，但是也造成了流量过大、速度过慢等问题。对于fscan还是更多应用在内网渗透中，而在内网渗透中对于薅洞的需求并不是太大，而是转向了对权限的获取。所以我精简了poc的数量，希望可以让它在内网中更快、更强。

# Delete Poc

2022年6月18日

```
zeit-nodejs-cve-2020-5284-directory-traversal.yml
xunchi-cnvd-2020-23735-file-read.yml
xiuno-bbs-cvnd-2019-01348-reinstallation.yml
wuzhicms-v410-sqli.yml
wordpress-ext-adaptive-images-lfi.yml
wordpress-cve-2019-19985-infoleak.yml
weiphp-path-traversal.yml
uwsgi-cve-2018-7490.yml
tvt-nvms-1000-file-read-cve-2019-20085.yml
tpshop-sqli.yml
tpshop-directory-traversal.yml
tongda-user-session-disclosure.yml
tongda-meeting-unauthorized-access.yml
thinkcmf-lfi.yml
phpshe-sqli.yml
thinkadmin-v6-readfile.yml
spring-cloud-cve-2020-5410.yml
spring-cloud-cve-2020-5405.yml
resin-cnnvd-200705-315.yml
resin-viewfile-fileread.yml
springcloud-cve-2019-3799.yml
seacms-sqli.yml
seacms-v654-rce.yml
seacmsv645-command-exec.yml
spark-webui-unauth.yml
seacms-rce.yml
seacms-before-v992-rce.yml
resin-inputfile-fileread-or-ssrf.yml
phpok-sqli.yml
cacti-weathermap-file-write.yml
spark-api-unauth.yml
ns-asg-file-read.yml
seeyon-wooyun-2015-148227.yml
bt742-pma-unauthorized-access.yml
seeyon-wooyun-2015-0108235-sqli.yml
seeyon-cnvd-2020-62422-readfile.yml
seeyon-a6-employee-info-leak.yml
74cms-sqli-2.yml
74cms-sqli-1.yml
74cms-sqli.yml
discuz-wooyun-2010-080723.yml
discuz-wechat-plugins-unauth.yml
discuz-v72-sqli.yml
discuz-ml3x-cnvd-2019-22239.yml
dedecms-url-redirection.yml
dedecms-membergroup-sqli.yml
dedecms-guestbook-sqli.yml
dedecms-cve-2018-7700-rce.yml
dedecms-cve-2018-6910.yml
dedecms-carbuyaction-fileinclude.yml
ecshop-rce.yml
ecshop-login-sqli.yml
ecshop-collection-list-sqli.yml
ecshop-cnvd-2020-58823-sqli.yml
phpmyadmin-cve-2018-12613-file-inclusion.yml
cisco-cve-2020-3452-readfile.yml
citrix-cve-2019-19781-path-traversal.yml
coldfusion-cve-2010-2861-lfi.yml
confluence-cve-2019-3396-lfi.yml
confluence-cve-2021-26085-arbitrary-file-read.yml
finecms-sqli.yml
fangweicms-sqli.yml
finereport-directory-traversal.yml
finereport-v8-arbitrary-file-read.yml
flink-jobmanager-cve-2020-17519-lfi.yml
metinfo-cve-2019-17418-sqli.yml
metinfo-cve-2019-16997-sqli.yml
metinfo-cve-2019-16996-sqli.yml
metinfo-file-read.yml
metinfo-lfi-cnvd-2018-13393.yml
elasticsearch-cve-2015-3337-lfi.yml
eea-info-leak-cnvd-2021-10543.yml
zzcms-zsmanage-sqli.yml
zcms-v3-sqli.yml
yungoucms-sqli.yml
xdcms-sql.yml
shiziyu-cms-apicontroller-sqli.yml
shopxo-cnvd-2021-15822.yml
samsung-wea453e-rce.yml
samsung-wea453e-default-pwd.yml
samsung-wlan-ap-wea453e-rce.yml
saltstack-cve-2021-25282-file-write.yml
ruoyi-management-fileread.yml
ruijie-eg-file-read.yml
mpsec-isg1000-file-read.yml
myucms-lfr.yml
msvod-sqli.yml
kingsoft-v8-file-read.yml
huawei-home-gateway-hg659-fileread.yml
exchange-cve-2021-26855-ssrf.yml
maccmsv10-backdoor.yml
maccms-rce.yml
citrix-cve-2020-8191-xss.yml
phpcms-cve-2018-19127.yml
php-cgi-cve-2012-1823.yml
```

# Add Poc

2022年6月18日

```
Atlassian Confluence 远程代码执行漏洞（CVE-2022-26134）
```



## 免责声明

本工具仅面向**合法授权**的企业安全建设行为，如您需要测试本工具的可用性，请自行搭建靶机环境。

为避免被恶意使用，本项目所有收录的poc均为漏洞的理论判断，不存在漏洞利用过程，不会对目标发起真实攻击和漏洞利用。

在使用本工具进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权。**请勿对非授权目标进行扫描。**

如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，我们将不承担任何法律及连带责任。

在安装并使用本工具前，请您**务必审慎阅读、充分理解各条款内容**，限制、免责条款或者其他涉及您重大权益的条款可能会以加粗、加下划线等形式提示您重点注意。
除非您已充分阅读、完全理解并接受本协议所有条款，否则，请您不要安装并使用本工具。您的使用行为或者您以其他任何明示或者默示方式表示接受本协议的，即视为您已阅读并同意本协议的约束。

