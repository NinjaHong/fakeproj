# 打印服务启动流程

## 文件准备

动态链接库文件

+ ZJSPrinting.dll
+ zxing.dll

注册服务脚本文件

+ v4.0.30319.bat

## 安装过程

1. 将文件【ZJSPrinting.dll】和【zxing.dll】放到目录 C:\Windows\Microsoft.NET\Framework\v4.0.30319 下。
2. 任意位置，右键文件【v4.0.30319.bat】，以管理员身份运行。
3. 若显示【成功注册了类型】则注册成功

## 测试

+ 设置一台可以使用的默认打印机，并将纸张大小设为100mmx180mm（注意必须保证纸张打印大小是这个规格，如果仅配置名称是100mmx180mm，实际大小并不一定是该规格），运行testZJSPrint.exe


# 附加---服务注销

## 文件准备

注销服务脚本文件

+ v4.0.30319_un.bat

## 安装过程

1. 任意位置，右键文件【v4.0.30319_un.bat】，以管理员身份运行。
2. 若显示【成功注销了类型】则注销成功
