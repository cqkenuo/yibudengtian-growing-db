“xxe注入漏洞”原理学习及实验挑战：  
https://portswigger.net/web-security/xxe  

xml entity学习资源：  
https://portswigger.net/web-security/xxe/xml-entities  
xml学习资源：  
https://www.w3schools.com/xml/default.asp  
实验1：利用xxe来查看文件  

实验2：使用xxe来执行ssrf攻击  

实验3：通过OAST技术来检测blind xxe  

实验4：利用blind xxe通过out-of-band来查看文件  

实验5：利用blind xxe通过错误消息来查看文件  

实验6：

实验7：

XInclude学习资源：  
https://www.xml.com/pub/a/2002/07/31/xinclude.html  
实验8：XInclude攻击  

实验9：通过文件上载执行xxe攻击  

0：执行xxe攻击  
0.1：检索服务器上的文件  
<!DOCTYPE foo [ <!ENTITY xxe SYSTEM "file:///etc/passwd"> ] >  
&xxe;  
