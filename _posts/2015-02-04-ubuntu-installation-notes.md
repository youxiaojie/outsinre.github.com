---
layout: post
title: Ubuntu 14.04 Installation Notes
---

1. sources.list apt
2. /etc/fstab, refer to Gentoo's installation notes.
    1. [MountingWindowsPartitions](https://help.ubuntu.com/community/MountingWindowsPartitions)
3. clear dash history (settings)
4. Chinese language support & sogou input
5. Chrome / flashplugin
6. Wifi certificate: /usr/share/ca-certificates/mozilla/AddTrust_External_Root.crt
7. texlive 2014; install windows & adobe fonts;
8. Configure locale in Ubuntu [Configure Locales in Ubuntu](https://www.thomas-krenn.com/en/wiki/Configure_Locales_in_Ubuntu)
8. 搜狗输入法。安装之前要先安装中文支持，就是上面的第四步。直接去搜狗官网下载deb文件，双击运行，默认打开了新得力，点击安装即可。默认还会安装fctix控制面板。一切顺利！ But you cannot set `LANG` OR `LC_CTYPE` to `zh_CN.GBK` or `zh_CN.GB18030`, otherwise you cannot input Chinese characters. I think Sogou currently does not support `GBK`, `GB2312` or `GB18030`.
