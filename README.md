# 锐捷NBR路由器远程命令执行漏洞

锐捷NBR路由器接口存在命令注入，攻击者可远程执行命令。


## 漏洞编号

CNVD-2021-09650

## 工具利用

python3 RG_NBR_rce.py -u http://127.0.0.1:1111 单个url测试

python3 RG_NBR_rce.py -c http://127.0.0.1:1111 cmdshell模式

python3 RG_NBR_rce.py -f url.txt 批量检测

![](./CNVD-2021-09650user.png)

## 免责声明

由于传播、利用此文所提供的信息而造成的任何直接或者间接的后果及损失，均由使用者本人负责，作者不为此承担任何责任。
