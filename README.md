# ssrf
autorepeater的ssrf自动化规则
该规则可以匹配json参数中的http参数，替换成你的dnslog，或者是vps的302跳转地址进行自动化ssrf挖掘


(?i)(?!\\)\"(https|http|file)://(.*?)?"


(?i)\\\"(https|http|file)://(.*?)?\"
![image](https://github.com/chenlinji34/ssrf/assets/126755230/a1b28c54-1dff-4fec-ad30-f5d430823231)
