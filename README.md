#### 0x01 程序简介

该程序主要是针对已保存在 Windows 系统上的程序密码进行解密。是该[文章](https://rcoil.me/2019/09/%E3%80%90%E7%BC%96%E7%A8%8B%E3%80%91SharpDecryptPwd/)的代码示例，以 `Assembly.Load` 的形式开源，有兴趣的朋友也可以反编译还原一下。不过，我觉得没必要，因为文章中该讲的已经讲解了。

目前支持 Navicat 系列、Xmanager 系列、TeamViewer、FileZilla 客户端、Foxmail、RealVNC 服务端、TortoiseSVN、WinSCP、Chrome 全版本。

***建议在用户权限下运行该程序***


#### 0x02 使用说明

```

SharpDecryptPwd.exe -Moudle
Moudel:
        -Navicat
        -Xmanager   Xshell,Xftp
        -TeamViewer
        -FileZilla
        -Foxmail
        -RealVNC
        -TortoiseSVN
        -WinSCP
		-Chrome
		-RDCMan
```



#### 0x03 更新日志

```
SharpDecryptPwd 2.2 20200930
============================================ ==========
[+] 添加 RDCMan 模块	

SharpDecryptPwd 2.1 20200808
============================================ ==========
[+] 添加 Chrome 模块	

SharpDecryptPwd 2.0 20200609
============================================ ==========
[-] 移除 SSMS 模块（可以去头像哥的 github 下载）
[+] 从主程序中分离模块代码，以 Assembly.Load 的形式开源

SharpDecryptPwd 1.7 20200405
============================================ ==========
[+] 添加 WinSCP 模块	

SharpDecryptPwd 1.6 20200322
============================================ ==========
[+] 添加 TortoiseSVN 模块	

SharpDecryptPwd 1.5 20200314
============================================ ==========
[+] 添加 RealVNC 服务端模块

SharpDecryptPwd 1.4 20191011
============================================ ==========
[+] 添加 Foxmail 模块	

SharpDecryptPwd 1.3 20190827
============================================ ==========
[+] 添加 Navicat PremiumSoft 模块

SharpDecryptPwd 1.2 20190826
============================================ ==========
[+] 添加 FileZilla 模块

SharpDecryptPwd 1.1 20190823
============================================ ==========
[+] 添加 SSMS 模块（引用 http://www.zcgonvh.com/post/SQL_Server_Management_Studio_saved_password_dumper.html）
[+] 添加 TeamView 模块(引用 https://www.t00ls.net)

SharpDecryptPwd 1.0 20190822
============================================ ==========
[+] 创建 SharpDecryptPwd 项目
[+] 添加 Xmanager 模块，支持 Xshell、Xftp
```

