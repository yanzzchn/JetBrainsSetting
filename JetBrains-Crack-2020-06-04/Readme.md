> JetBrains全系列软件激活教程，共有两种方法，喜欢哪种用哪种。另外附上JetBrains系列软件的汉化包以及中文设置教程，希望大家喜欢。
> 方法可能随时失效，最新文章请查看原文：https://macwk.com/article/jetbrains-crack

## 写在前面

#### MacWk.com建议大家去 [JetBrains官网](https://www.jetbrains.com/) 下载JetBrains系列工具的官方版，然后使用本教程方法激活。

Jetbrains 自2020年1月起大量封杀激活码，现在几乎没有可用的激活码了，X宝上的都已经关店了，那些卖激活码的随时准备坑钱跑路。没有激活码了怎么办？

今天就送给大家一份大礼： Jetbrains全系列产品 2020.1.2 及以下版本最新注册服务器 License Server 的破解工具（理论上适用于目前 Jetbrains 所有新老版本），可使用它来激活你手头上所有的 Jetbrains 产品。

测试可成功激活JetBrains以下版本（支持低于以下版本的激活）：

> IntelliJ IDEA 2020.1.2 激活、AppCode 2020.1.2 激活、CLion 2020.1.2 激活、DataGrip 2020.1.2 激活、GoLand 2020.1.2 激活、PhpStorm 2020.1.2 激活、PyCharm 2020.1.2 激活、Rider 2020.1.2 激活、RubyMine 2020.1.2 激活、WebStorm 2020.1.2 激活

2020.1.2 有部分人会出现激活失败，暂时无解决方法，出现的请下载 2020.1.1，然后使用旧版本来激活，[点我下载旧版本激活工具](https://545c.com/file/19991453-436522151)，更新于: 2020-06-04 13:38

已更新v3.2.1, 支持Jetbrains平台付费插件，支持 2020.1.2 及以下所有版本。如果高于这个版本激活可能会不成功，请知悉！

## 下载

[JetBrains破解文件.zip](https://545c.com/file/19991453-447219333)

> 已修复激活后还弹出激活窗口问题。

## 配置

### 新版配置方式（推荐）

> 如果你之前使用的是旧版本的配置方式想切换成新的配置方式，请先点击`Help -> Edit Custom VM Options ..`，在打开的 `xxx.vmoptions`中将之前添加的配置文件删除即可，继续使用旧的配置方式也是可以的。

1. 解压 JetBrains破解文件.zip，将 `jetbrains-agent.jar`、`important.txt`这两个文件放到你喜欢放的任意位置。
2. 启动你的IDE如WebStorm，如果启动后需要注册激活，请选择『试用』，（Evaluate for free）。
3. 将 `jetbrains-agent.jar` 拖进IDE窗口，点 『Restart』 按钮重启IDE。
4. 在弹出的 `JetbrainsAgent 配置助手` 对话框中，选择激活方式，点击『安装』按钮，然后点击『是』（如果你是无外网环境，在对话框中勾选：我无法访问外网 选项，如银行、公安内网）。
5. 重启你的IDE。

总结：打开ide然后选择试用，接着不需要进入项目，直接将.jar文件拖进ide窗口，然后按照提示安装即可。

### 旧版配置方式

1. 解压 JetBrains破解文件.zip，将 `jetbrains-agent.jar`、`important.txt`，文件放到你喜欢放的任意位置。
2. 运行 JetBrains的软件,以 WebStorm 为例，点击`Help -> Edit Custom VM Options ..` (如果提示是否要创建文件，请点 "Yes")
3. 在打开的 `xxx.vmoptions` 行未添加：`-javaagent:/absolute/path/to/jetbrains-agent.jar`（切记将 `/absolute/path/to/` 修改为你的路径）
4. 重启你的IDE。

> 需要注意的是: 一定要自己确认好路径(不要使用中文路径)，填错会导致IDE打不开！最好使用绝对路径。`xxx.vmoptions` 内只允许有一个 `-javaagent` 参数。

##### `xxx.vmoptions` 路径示例:

| 系统    | 代码                                          |
| ------- | --------------------------------------------- |
| mac     | -javaagent:/home/macwk/jetbrains-agent.jar    |
| linux   | -javaagent:/home/macwk/jetbrains-agent.jar    |
| windows | -javaagent:C:\Users\macwk\jetbrains-agent.jar |

> 如果`vmoptions`还是不小心填错了导致软件打不开，请参考这篇文章补救：[点我查看](https://intellij-support.jetbrains.com/hc/en-us/articles/206544519)

## 激活

1. 点击IDE菜单 `Help" -> Register...` 或 `Configure -> Manage License...`
2. 选择激活模式，有两种模式，您可以任选一种：

#### Activation Code 模式

打开包内的`激活码.txt`，全选复制后粘贴到 `Activation Code` 下面的输入框中，然后点击`Activate`，大功告成，有效期至2089年。(您也可以[生成专属激活码](https://zhile.io/custom/license))。

#### License server 模式

`Server Address`地址填入：`http://fls.jetbrains-agent.com` 然后点击`Activate`，支持https。(如果点击出现`Please wait...`后没有任何变化，那请使用 `Activation Code 模式`)。

#### 异常

1. 如果激活窗口一直弹出 `error 1653219`，请去hosts文件里移出 jetbrains 相关的Host条目。
2. `License key is in legacy format == Key invalid`，表示agent配置未生效。



### 付费插件使用

> 如果您选择了 License server 模式 则不需要使用下面的 Activation code 激活，如果您使用 Activation code 模式激活，则必须使用下面的 Activation code 激活码：

插件 Activation code 激活码：

```
9H0GH22VQT-eyJsaWNlbnNlSWQiOiI5SDBHSDIyVlFUIiwibGljZW5zZWVOYW1lIjoiaHR0cHM6Ly96aGlsZS5pbyIsImFzc2lnbmVlTmFtZSI6IiIsImFzc2lnbmVlRW1haWwiOiIiLCJsaWNlbnNlUmVzdHJpY3Rpb24iOiIiLCJjaGVja0NvbmN1cnJlbnRVc2UiOmZhbHNlLCJwcm9kdWN0cyI6W3siY29kZSI6IlBXTEFORyIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQU0NJUElPIiwiZmFsbGJhY2tEYXRlIjoiMjA4OS0wNy0wNyIsInBhaWRVcFRvIjoiMjA4OS0wNy0wNyJ9LHsiY29kZSI6IlBKRENMRUFOUkVBRCIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQQUVNIiwiZmFsbGJhY2tEYXRlIjoiMjA4OS0wNy0wNyIsInBhaWRVcFRvIjoiMjA4OS0wNy0wNyJ9LHsiY29kZSI6IlBKRVRGT1JDRVIiLCJmYWxsYmFja0RhdGUiOiIyMDg5LTA3LTA3IiwicGFpZFVwVG8iOiIyMDg5LTA3LTA3In0seyJjb2RlIjoiUE1ETkFWIiwiZmFsbGJhY2tEYXRlIjoiMjA4OS0wNy0wNyIsInBhaWRVcFRvIjoiMjA4OS0wNy0wNyJ9LHsiY29kZSI6IlBMQVJBVkVMIiwiZmFsbGJhY2tEYXRlIjoiMjA4OS0wNy0wNyIsInBhaWRVcFRvIjoiMjA4OS0wNy0wNyJ9LHsiY29kZSI6IlBNQU5JRk9MRCIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQSFlCUklTQ09NTUVSQ0UiLCJmYWxsYmFja0RhdGUiOiIyMDg5LTA3LTA3IiwicGFpZFVwVG8iOiIyMDg5LTA3LTA3In0seyJjb2RlIjoiUFZMT0ciLCJmYWxsYmFja0RhdGUiOiIyMDg5LTA3LTA3IiwicGFpZFVwVG8iOiIyMDg5LTA3LTA3In0seyJjb2RlIjoiUEJJU0oiLCJmYWxsYmFja0RhdGUiOiIyMDg5LTA3LTA3IiwicGFpZFVwVG8iOiIyMDg5LTA3LTA3In0seyJjb2RlIjoiUENPREVBSUlDRUJFUkciLCJmYWxsYmFja0RhdGUiOiIyMDg5LTA3LTA3IiwicGFpZFVwVG8iOiIyMDg5LTA3LTA3In0seyJjb2RlIjoiUE1JTkJBVElTIiwiZmFsbGJhY2tEYXRlIjoiMjA4OS0wNy0wNyIsInBhaWRVcFRvIjoiMjA4OS0wNy0wNyJ9LHsiY29kZSI6IlBNRVNPTlNZTlRBWCIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQUk9OIiwiZmFsbGJhY2tEYXRlIjoiMjA4OS0wNy0wNyIsInBhaWRVcFRvIjoiMjA4OS0wNy0wNyJ9LHsiY29kZSI6IlBaRU5VTUwiLCJmYWxsYmFja0RhdGUiOiIyMDg5LTA3LTA3IiwicGFpZFVwVG8iOiIyMDg5LTA3LTA3In0seyJjb2RlIjoiUE9QRU5BUEkiLCJmYWxsYmFja0RhdGUiOiIyMDg5LTA3LTA3IiwicGFpZFVwVG8iOiIyMDg5LTA3LTA3In0seyJjb2RlIjoiUENNQUtFUExVUyIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQU1dQTFVHSU4iLCJmYWxsYmFja0RhdGUiOiIyMDg5LTA3LTA3IiwicGFpZFVwVG8iOiIyMDg5LTA3LTA3In0seyJjb2RlIjoiUE1SSU5URUdFRSIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQSkZPUk1ERVNJR05FUiIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQU0ZDQyIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQUE9KT1RPSlNPTlNDSCIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQR0RPQyIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQTVlCQVRJU0xPRyIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQT0ZGSUNFRkxPT1IiLCJmYWxsYmFja0RhdGUiOiIyMDg5LTA3LTA3IiwicGFpZFVwVG8iOiIyMDg5LTA3LTA3In0seyJjb2RlIjoiUFNNQVJUSlVNUCIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQQ1lQUkVTU1BSTyIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQSUVESVMiLCJmYWxsYmFja0RhdGUiOiIyMDg5LTA3LTA3IiwicGFpZFVwVG8iOiIyMDg5LTA3LTA3In0seyJjb2RlIjoiUEJBU0hTVVBQT1JUUFJPIiwiZmFsbGJhY2tEYXRlIjoiMjA4OS0wNy0wNyIsInBhaWRVcFRvIjoiMjA4OS0wNy0wNyJ9LHsiY29kZSI6IlBCUldKViIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQT1JDSElERSIsImZhbGxiYWNrRGF0ZSI6IjIwODktMDctMDciLCJwYWlkVXBUbyI6IjIwODktMDctMDcifSx7ImNvZGUiOiJQUkRGQU5EU1BBUlFMIiwiZmFsbGJhY2tEYXRlIjoiMjA4OS0wNy0wNyIsInBhaWRVcFRvIjoiMjA4OS0wNy0wNyJ9LHsiY29kZSI6IlBDUkVWSUVXIiwiZmFsbGJhY2tEYXRlIjoiMjA4OS0wNy0wNyIsInBhaWRVcFRvIjoiMjA4OS0wNy0wNyJ9XSwiaGFzaCI6IjEyNzk2ODc3LzAiLCJncmFjZVBlcmlvZERheXMiOjcsImF1dG9Qcm9sb25nYXRlZCI6ZmFsc2UsImlzQXV0b1Byb2xvbmdhdGVkIjpmYWxzZX0=-UGz/GQqVWovQ9er6xOiDOZAcKLWDuuMk4+EMcupPokw/eheW+PgGqWQso7fUH6rw9ffcfjPSGbu7o+ZI/gAVQR5DwG3j3gwaKFYLmVp6cnHDel2j5nAPxCPkw8nT/oTUe1nazsVwxlPe8Vtrl8HI1sOYxOv2klAfY8/+fCBmcfLivrD0l+aStXTZnZezrq3cfUpPMN9Sn3vbhGXpJLhVtZU5eW3RL6zwLGAmAME17EkHygE5+d4uh0cDl3uNEmxxmgG5vx2yN3fuJjyvQbY4PpN7rH2SlGZLpyTsXPpqWDReD7Qnkw7xHuysuhFk+stLpUwsrcyWyvhmO1LXtZVvZw==-MIIElTCCAn2gAwIBAgIBCTANBgkqhkiG9w0BAQsFADAYMRYwFAYDVQQDDA1KZXRQcm9maWxlIENBMB4XDTE4MTEwMTEyMjk0NloXDTIwMTEwMjEyMjk0NlowaDELMAkGA1UEBhMCQ1oxDjAMBgNVBAgMBU51c2xlMQ8wDQYDVQQHDAZQcmFndWUxGTAXBgNVBAoMEEpldEJyYWlucyBzLnIuby4xHTAbBgNVBAMMFHByb2QzeS1mcm9tLTIwMTgxMTAxMIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEA5ndaik1GD0nyTdqkZgURQZGW+RGxCdBITPXIwpjhhaD0SXGa4XSZBEBoiPdY6XV6pOfUJeyfi9dXsY4MmT0D+sKoST3rSw96xaf9FXPvOjn4prMTdj3Ji3CyQrGWeQU2nzYqFrp1QYNLAbaViHRKuJrYHI6GCvqCbJe0LQ8qqUiVMA9wG/PQwScpNmTF9Kp2Iej+Z5OUxF33zzm+vg/nYV31HLF7fJUAplI/1nM+ZG8K+AXWgYKChtknl3sW9PCQa3a3imPL9GVToUNxc0wcuTil8mqveWcSQCHYxsIaUajWLpFzoO2AhK4mfYBSStAqEjoXRTuj17mo8Q6M2SHOcwIDAQABo4GZMIGWMAkGA1UdEwQCMAAwHQYDVR0OBBYEFGEpG9oZGcfLMGNBkY7SgHiMGgTcMEgGA1UdIwRBMD+AFKOetkhnQhI2Qb1t4Lm0oFKLl/GzoRykGjAYMRYwFAYDVQQDDA1KZXRQcm9maWxlIENBggkA0myxg7KDeeEwEwYDVR0lBAwwCgYIKwYBBQUHAwEwCwYDVR0PBAQDAgWgMA0GCSqGSIb3DQEBCwUAA4ICAQBonMu8oa3vmNAa4RQP8gPGlX3SQaA3WCRUAj6Zrlk8AesKV1YSkh5D2l+yUk6njysgzfr1bIR5xF8eup5xXc4/G7NtVYRSMvrd6rfQcHOyK5UFJLm+8utmyMIDrZOzLQuTsT8NxFpbCVCfV5wNRu4rChrCuArYVGaKbmp9ymkw1PU6+HoO5i2wU3ikTmRv8IRjrlSStyNzXpnPTwt7bja19ousk56r40SmlmC04GdDHErr0ei2UbjUua5kw71Qn9g02tL9fERI2sSRjQrvPbn9INwRWl5+k05mlKekbtbu2ev2woJFZK4WEXAd/GaAdeZZdumv8T2idDFL7cAirJwcrbfpawPeXr52oKTPnXfi0l5+g9Gnt/wfiXCrPElX6ycTR6iL3GC2VR4jTz6YatT4Ntz59/THOT7NJQhr6AyLkhhJCdkzE2cob/KouVp4ivV7Q3Fc6HX7eepHAAF/DpxwgOrg9smX6coXLgfp0b1RU2u/tUNID04rpNxTMueTtrT8WSskqvaJd3RH8r7cnRj6Y2hltkja82HlpDURDxDTRvv+krbwMr26SB/40BjpMUrDRCeKuiBahC0DCoU/4+ze1l94wVUhdkCfL0GpJrMSCDEK+XEurU18Hb7WT+ThXbkdl6VpFdHsRvqAnhR2g4b+Qzgidmuky5NUZVfEaZqV/g==
```

已支持付费插件列表：

- [JetForcer | The Smartest Force.com IDE](https://plugins.jetbrains.com/plugin/9238-jetforcer--the-smartest-force-com-ide/)
- [Java Antidecompiler](https://plugins.jetbrains.com/plugin/11560-java-antidecompiler/)
- [OpenAPI Editor](https://plugins.jetbrains.com/plugin/12887-openapi-editor/)
- [CMake Plus](https://plugins.jetbrains.com/plugin/12869-cmake-plus/)
- [ZenUML support](https://plugins.jetbrains.com/plugin/12437-zenuml-support/)
- [Markdown Navigator Enhanced](https://plugins.jetbrains.com/plugin/7896-markdown-navigator-enhanced/)
- [AEM Support](https://plugins.jetbrains.com/plugin/9863-aem-support/)
- [JavaDoc Clean Read](https://plugins.jetbrains.com/plugin/10828-javadoc-clean-read/)
- [Manifold](https://plugins.jetbrains.com/plugin/10057-manifold/)
- [Shopware](https://plugins.jetbrains.com/plugin/7410-shopware/)
- [OrchidE](https://plugins.jetbrains.com/plugin/12626-orchide/)
- [POJO to JSON Schema](https://plugins.jetbrains.com/plugin/13733-pojo-to-json-schema/)
- [Laravel Idea](https://plugins.jetbrains.com/plugin/13441-laravel-idea/)
- [Code Review for Bitbucket](https://plugins.jetbrains.com/plugin/13538-code-review-for-bitbucket/)
- [JFormDesigner (Marketplace Edition)](https://plugins.jetbrains.com/plugin/12621-jformdesigner-marketplace-edition-/)
- [hybris integration](https://plugins.jetbrains.com/plugin/7525-hybris-integration/)
- [MinBatis](https://plugins.jetbrains.com/plugin/13720-minbatis/)
- [Scipio ERP Integration](https://plugins.jetbrains.com/plugin/12108-scipio-erp-integration/)
- [Meson Syntax Highlighter](https://plugins.jetbrains.com/plugin/13269-meson-syntax-highlighter/)
- [MyBatis Log Plugin](https://plugins.jetbrains.com/plugin/13905-mybatis-log-plugin/)
- [Wolfram Language](https://plugins.jetbrains.com/plugin/7232-wolfram-language/)
- [SystemVerilog](https://plugins.jetbrains.com/plugin/10695-systemverilog/)
- [Generate Document](https://plugins.jetbrains.com/plugin/13086-generate-document/)
- [RON (Rusty Object Notation)](https://plugins.jetbrains.com/plugin/12635-ron-rusty-object-notation-/)
- [Iceberg](https://plugins.jetbrains.com/plugin/12984-iceberg/)
- [Smart Jump](https://plugins.jetbrains.com/plugin/14053-smart-jump/)
- [Merge Request Integration EE - Code Review for GitLab](https://plugins.jetbrains.com/plugin/13615-merge-request-integration-ee--code-review-for-gitlab/)
- [Iedis 2](https://plugins.jetbrains.com/plugin/12634-iedis-2/)
- [BashSupport Pro](https://plugins.jetbrains.com/plugin/13841-bashsupport-pro/)
- [OfficeFloor](https://plugins.jetbrains.com/plugin/13151-officefloor/)
- [Salesforce B2C Commerce (SFCC)](https://plugins.jetbrains.com/plugin/13668-salesforce-b2c-commerce-sfcc-/)
- [RDF and SPARQL](https://plugins.jetbrains.com/plugin/13838-rdf-and-sparql/)
- [Cypress-Pro](https://plugins.jetbrains.com/plugin/13987-cypress-pro/)
- [AutoCode for Java](https://plugins.jetbrains.com/plugin/10904-autocode-for-java/)





以上步骤操作完成后激活就结束了，如果有需要 JetBrains 中文汉化包的可以继续往下看。此方法来自于：[zhile.io](https://zhile.io/)

所有付费插件列表查看：[点我查看](https://plugins.jetbrains.com/search?isPaid=true)





------

## 中文汉化包

JetBrains 系列汉化包可用于：

- Android Studio 3.5 汉化包
- CLion 2019.3 汉化包
- DataGrip 2019.3 汉化包
- GoLand 2019.3 汉化包
- IntelliJ IDEA 2019.3 汉化包
- PhpStorm 2019.3 汉化包
- PyCharm 2019.3 汉化包
- Rider 2019.3 汉化包
- RubyMine 2019.3 汉化包
- WebStorm 2019.3 汉化包

汉化来自于：[pingfangx.com](https://www.pingfangx.com/)

### 下载

[GitHub下载](https://github.com/pingfangx/TranslatorX)

[百度网盘下载](https://pan.baidu.com/s/1bVltZl7DITVgHVmmhLAuZw)(提取码:2t81)

### 使用

将 resources_zh_CN_*.jar ，放到软件安装路径下的 **lib** 目录中，重启软件即可

- 注意是 **lib** 不是 **bin**
- 不需要重命名，不需要解压，不需要删除任何 jar 包，不会覆盖任何 jar 包
- 软件安装路径的 lib 目录示例 `D:\software\JetBrains\AndroidStudio\lib`
- 该目录下应该有一个文件: resources_en.jar 如果没有，说明没有找对路径
- MAC 用户请在 Finder > 应用程序 中找到软件，右键 > 显示包内容

### 汉化不生效

> 原因是因为当前语言环境不是中文（zh_CN）或者一些其它诡异的原因导致的，通过以下方法可以解决：

请打开软件，选择 `Help → Edit Custom VM Options...` ，加上两行

```
-Duser.language=zh  
-Duser.region=CN 
```

然后重启软件

### 设置打不开

系统原本的 `resources_en.jar` 被损坏，请重新安装恢复该 jar 包，按正确 [使用方法] 重新使用汉化包，常见原因：

- 不需要将汉化包内容解压到 `resources_en.jar` 中（这是通常网上不正确的汉化包使用方法）
- 不需要重命名替换

#### 汉字乱码/中文显示为框框

当前字体不支持中文显示，请到 `File → Settings → Appearance & Behavior → Appearance →` 勾选 `Override default fonts by (not recommended)`，选择 `Microsoft YaHei` 或者其他中文字体。