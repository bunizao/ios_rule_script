# 🧸 Amazon

## 前言

![](https://shields.io/badge/-移除重复规则-ff69b4) ![](https://shields.io/badge/-DOMAIN与DOMAIN--SUFFIX合并-green) ![](https://shields.io/badge/-DOMAIN--SUFFIX间合并-critical) ![](https://shields.io/badge/-IP--CIDR(6)合并-blueviolet) ![](https://shields.io/badge/-MITM--HOSTNAME合并-brightgreen) ![](https://shields.io/badge/-正则推导HOSTNAME-033da7) 

Amazon规则由《RULE GENERATOR 规则生成器》自动生成。

分流规则是互联网公共服务的域名和IP地址汇总，所有数据均收集自互联网公开信息，不代表我们支持或使用这些服务。

请通过我国(中华人民共和国)合法的互联网出入口信道访问规则中的地址，并确保在使用过程中符合相关法律法规。

## 规则统计

最后更新时间：2022-05-21 00:51:08

各类型规则统计：
| 类型 | 数量(条)  | 
| ---- | ----  |
| DOMAIN-KEYWORD | 1  | 
| DOMAIN-SUFFIX | 176  | 
| IP-CIDR | 15  | 
| URL-REGEX | 1  | 
| USER-AGENT | 2  | 
| TOTAL | 195  | 


## Stash 

#### 使用说明
- Amazon.yaml，请使用 behavior: classical。
- URL-REGEX类型的规则，在HTTPS协议中，需要配合MITM使用。规则生成器已尝试推导MITM的配置Amazon_MITM.stoverride，仅供参考。

#### 配置建议
- Amazon.yaml 单独使用。

#### 规则链接
**MASTER分支 (每日更新)**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Stash/Amazon/Amazon.yaml

**MASTER分支 CDN (每日更新)**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Stash/Amazon/Amazon.yaml

**RELEASE分支 (不定时更新)**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Stash/Amazon/Amazon.yaml

**RELEASE分支CDN (不定时更新)**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Stash/Amazon/Amazon.yaml

## 子规则/排除规则


当前分流规则，未包含其他子规则。

## 数据来源

《Amazon》的数据来自以下链接，如与本项目的《Amazon》规则混合使用，可能会造成规则大量重复。

- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Amazon.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Services/Amazon.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/PROXY/Amazon.list


感谢以上规则作者的辛勤付出（排名不分先后）。

## 最后

### 感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) [@vhdj](https://github.com/vhdj)

提供规则数据源及改进建议。

### 其他

请不要对外宣传本项目。