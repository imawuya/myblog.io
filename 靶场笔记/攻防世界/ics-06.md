# ics-06

# 所需工具：burpsuite

# 题目：

# 解题思路
点进靶场链接后，乱点一同，只有报表中心有响应，点进去后发现 ?id=1 ,修改了id的值也无法改变。
![image](https://github.com/imawuya/My-notes/assets/93590614/843f8d21-a865-4c6a-b35c-f81c4b861512)
<br>

使用burp进行抓包，发现参数只能是纯数字，尝试使用爆破：
![image](https://github.com/imawuya/My-notes/assets/93590614/83e1397f-d54c-4a68-8943-79d3ea8cedc0)
<br>

设置爆破参数：
![image](https://github.com/imawuya/My-notes/assets/93590614/ad393810-089e-4292-94e7-686d5b47b14c)
<br>

任务执行结束后发现2333，发现了flag
![image](https://github.com/imawuya/My-notes/assets/93590614/56a89223-c60b-4276-b363-554c0f636ab0)
![image](https://github.com/imawuya/My-notes/assets/93590614/ec4eb688-2e22-4593-a1f8-23d80b57cef2)
