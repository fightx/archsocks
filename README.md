# archsocks
SOCKS代理服务 - 免费加速Google搜索、Gmail、维基百科，加速其它网站只需少量费用。

# 下载

[下载 Windows 版](http://104.245.8.176/files/archsocks-setup.exe)

[下载 Linux / OS X 版](http://104.245.8.176/files/archsocks.tar.gz)

# 特性

* 模拟HTTP流量: 完全模拟正常上网流量并采用80端口，无视企业防火墙。
* 多节点: 拥有多个代理节点自动切换，上网更快更稳定。
* 自动流量分类: 只对需要代理的网站使用代理，不会减慢国内网站速度，节省代理流量。
* 本地SOCKS代理: 使用本地SOCKS代理接口方式，比VPN和SSH方式更方便和稳定。

# 价格

*所有套餐都可以按月付，付款方式在客户端界面里*

流量/周期 | Google/Gmail/维基百科 | 4GB/月 | 16GB/月 | 32GB/月 | 64GB/月
---------- | --------------------- | ------ | ------- | ------- | -------
价格      | 永久免费              | 2元/月 | 4元/月  | 6元/月  | 10元/月

# 安装

## Windows

运行下载的.exe安装程序。安装完后服务会自动启动，同时添加自身到Windows启动组（会随Windows启动而自启动）。

## Linux / OSX

程序以Python源码形式发布，需要确保系统已安装[Python 3.4](https://www.python.org)。
解压下载的压缩文件后运行里面的archsocks文件以启动程序。

# 客户端操作界面

在安装完成后，用浏览器打开网址[http://127.0.0.1:9501](http://127.0.0.1:9501)即可查看设置教程/程序运行状态/当前流量用量/购买链接。

![截图](https://raw.githubusercontent.com/archsocks/archsocks/master/screenshot.png)

# 联系方式

请发[Issue](https://github.com/archsocks/archsocks/issues)或发邮件至`archsocks [at] gmail.com`。
