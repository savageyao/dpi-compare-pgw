#定向流量比对工具
## 简介
基于Python3，将用户的DPI明细与从XGW导出的定向流量规则文件进行IP/URL比对，分别输出匹配上和未匹配上的汇总和明细结果
为了解放运营商同事的比对繁琐工作

#入文件格式要求
1. Excel 2010格式，后缀为xlsx

2.单用户的DPI明细，F列为目的IP，K列为URL

3.xGW导出的dpi规则文件（目前支持中兴），AE列为RG值，H/I列为目的IP和掩码，T列为URL
