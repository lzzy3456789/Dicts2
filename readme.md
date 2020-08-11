### 渗透测试人员专用精简化字典

----

Dictionary for penetration testers happy hacker 🎉

该项目为了2020年即将到来的护网准备。

收集了各大开源字典并进行了整合精简化和去重处理。



#### 字典说明

Dictionary description

```note
└── american-wordlist [美国人相关字典]
└── chinese-wordlist [中国人相关字典]
└── dns-wordlist [域名爆破字典]
└── passwords [常用密码集合]
└── all-attacks [通用攻击载荷]
  ├── all-attacks-payloads.txt [所有攻击有效载荷]
  ├── interesting-metacharacter [有趣的鸡吧元字符]
  ├── null-fuzz.txt [空字符模糊测试]
  └── url-hex-fuzz.txt [URL十六进制模糊测试]
└── file-include [文件包含]
  ├── common-unix-file-locations.txt [常见的unix文件通用位置]
  ├── common-windows-file-locations.txt [windows文件通用位置]
  └── lfi-scanner [文件包含通用扫描检测有效攻击载荷]
└── file-upload [文件上传]
  ├── alt-extensions-asp.txt [ASP脚本扩展名]
  ├── alt-extensions-jsp.txt [JSP脚本扩展名]
  ├── alt-extensions-perl.txt [Perl脚本扩展名]
  ├── alt-extensions-php.txt [PHP脚本扩展名]
  └── file-extension-list.txt [通用文件扩展名列表]
└── http-protocol [HTTP协议]
  ├── http-methods-fuzz.txt [HTTP请求方法模糊测试]
  └── user-agents-fuzz.txt [UA请求方法模糊测试]
└── JSONP [JSONP劫持漏洞]
  └── callback-param.txt [JSONP劫持漏洞回调参数]
└── os-command-execution [操作系统命令执行]
  ├── command-execution-vuln-scanner.txt [命令执行漏洞扫描]
  ├── linux-commands-fuzz.txt [Linux命令参数模糊测试]
  ├── osx-commands-fuzz.txt [OSX命令参数模糊测试]
  ├── windows-cmd-commands-fuzz.txt [Windows-CMD命令参数模糊测试]
  └── powershell-commands-fuzz.txt [PowerShell命令参数模糊测试]
└── param-dict [参数字典]
  └── parameter-fuzz.txt [参数模糊测试]
└── sql-injection [SQL注入]
 	├── blind-injection-fuzz.txt [盲注模糊测试]
  ├── login-password-injection-fuzz.txt [万能密码登陆模糊测试]
  ├── mssql-payloads-fuzz.txt [MSSQL注入攻击载荷模糊测试]
  ├── mysql-payloads-fuzz.txt [MYSQL注入攻击载荷模糊测试]
  └── oracle-payloads-fuzz.txt [ORACLE注入攻击载荷模糊测试]
└── ssrf [SSRF漏洞]
  └── localhost-fuzz.txt [本地服务器地址模糊测试]  
└── web-directory-attack [WEB目录攻击]
  ├── api-fuzz.txt [API路径模糊测试]
  ├── ctf-fuzz.txt [CTF路径模糊测试]
  ├── dir-fuzz.txt [通用路径模糊测试]
  ├── image-size-fuzz.txt [图像大小模糊测试]
  ├── js-file-fuzz.txt [JS文件模糊测试]
  └── php-file-fuzz.txt [PHP文件模糊测试]
└── xml-attacks [XML攻击]
  └── xml-attacks.txt [XML攻击有效载荷]
└── XSS [跨站脚本攻击]
  ├── html-tags.txt [HTML标签列表]
  ├── javascript-events-tags.txt [Javascript On事件标签列表]
  └── xss-payloads-fuzz.txt [XSS通用攻击有效载荷模糊测试]
```



**参考**:  [fuzzDicts](https://github.com/TheKingOfDuck/fuzzDicts) | [fuzzdb ](https://github.com/fuzzdb-project/fuzzdb)| [Dict](https://github.com/NS-Sp4ce/Dict)  | ...

**更新日期**：20200811



持续更新中😊...

Continually updated...

