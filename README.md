VulnSituation
=

2018年本科毕设（漏洞态势感知）的部分内容。包括了从NVD上爬取CVE的漏洞代码和补丁代码；静态分析CVE的漏洞代码是否在指定内核版本源码中（精确到函数粒度，既能够判断漏洞代码是否存在于CVE指明的特定的函数中）；一个简单的BPNN用于当时对一些数据关联性的归纳；一些小工具。

内容可以参考下PPT

安装所需python包：
```
pip install bs4 xlwt xlrd xlutils xlsxwriter requests numpy lxml
```