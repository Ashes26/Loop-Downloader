# Loop-Downloader
一个可以循环下载指定URL的脚本<br>
最好使用Ubuntu，否则可能会有奇奇怪怪的问题出现<br>
Windows版本支持Windows 7及以上，或Windows Server 2012及以上<br>
Android版本需要手机支持bash，curl，echo命令<br>
下载Loop-downloader-Android.sh到本地<br>
打开juiceSSH，创建一个本地连接<br>
cd到文件所在位置执行
```
bash Loop-downloader-Android.sh
```
## 使用：
Linux：
```
wget --no-check-certificate https://cdn.jsdelivr.net/gh/Ashes26/Loop-Downloader@main/Loop-Downloader.sh -O Loop-Downloader.sh && bash Loop-Downloader.sh
```
Windows：
```
curl --output Loop-Downloader-Windows.bat -s https://img.typeboom.com/Github_File/Loop-Downloader-Windows.bat && Loop-Downloader-Windows.bat
```
Android：
```
bash Loop-downloader-Android.sh
```
## 测试链接示例：
```
http://cachefly.cachefly.net/200mb.test
```
```
http://lg-sj.racknerd.com/1000MB.test
```
```
https://mirrors.tuna.tsinghua.edu.cn/ubuntu-releases/bionic/ubuntu-18.04.5-live-server-amd64.iso
```
```
http://speedtest-nyc1.digitalocean.com/1gb.test
```
## 使用截图：
![Linux](https://img.typeboom.com/pic/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202021-06-07%20204858.png)

![Windows10](https://img.typeboom.com/pic/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202021-06-07%20205252.png)
备用Linux版一键脚本：
```
https://raw.githubusercontent.com/Ashes26/Loop-Downloader/main/Loop-Downloader.sh
```
