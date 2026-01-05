本补丁合集专门针对 Steam客户端脱壳后，使用KrKr引擎（包括KrKrZ）运行游戏时出现的常见错误提供修复方案。主要解决以下两类问题：

1.KrKr找不到krkrsteam.dll
2.KrKrZ提示程序损坏

适用于逆向工程研究、学习分析、资源解包等合法用途，严禁用于任何违法侵权行为。

如何使用？
直接扔目录替换即可

安全性与可靠性？
请使用杀毒软件尽情扫描，上传前已经过火绒扫描测试
若不信任仓库补丁上huorong.cn，并且扔沙盒检查
若反对此仓库内容，请勿使用本仓库软件，本仓库遵循MIT协议

误报与高危操作
江民杀毒误报，因为KrKrZ程序独有的的加密方式导致在打开时候会创建CXDEC加密解密dll
wamsoft给KiriKiriZ加了个Cxdec，游戏运行的时候会往下面这个路径释放一个DLL：C:\Users{用户名}\AppData\Local\Temp\krkr_{随机12位字符}_{随机8位字符}_{随机5位字符}
路径的生成在如下位置：
c:\Users\Administrator\AppData\Local\Temp\krkr_55f5bc686b5b_249498078_6884\e4f4b1858b56.dll
被误判高危操作即释放可执行文件dll

加密解密原理引用请查看
https://www.kungal.com/topic/2670
