# Netgear R8300 upnpd PreAuth RCE 漏洞


## 漏洞环境

需要先构建 buildroot 环境，交叉编译得到 `nvram.so`：

```
$ arm-buildroot-linux-uclibcgnueabi-gcc -Wall -fPIC -shared nvram.c -o nvram.so
```

## 漏洞复现

## 参考链接

- https://kb.netgear.com/000062158/Security-Advisory-for-Pre-Authentication-Command-Injection-on-R8300-PSV-2020-0211
- https://ssd-disclosure.com/ssd-advisory-netgear-nighthawk-r8300-upnpd-preauth-rce/
- https://paper.seebug.org/1311/
