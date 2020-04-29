# regex snippets
![](https://img.shields.io/github/package-json/v/mxggle/regex-snippets)

JavaScript常用正则表达式snippets
## Supported languages (file extensions)
- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)
- Html (.html)
- Vue (.vue)
## Features
包含开发过程中常用到的一些正则表达式
| Trigger  | Content |
| -------: | ------- |
| `!regphone`   | 电话号码 `/^1[3|5|8|7]\d{9}$/` |
| `!regemai`   | 电子邮箱 `/^\w+@([0-9a-zA-Z]+[.])+[a-z]{2,4}$/`|
| `!regurl`   | 包含http(s) 协议的URL `/https?:\/\/(www\.)?[-a-zA-Z0-9@:%._\+~#=]{2,256}\.[a-z]{2,6}\b([-a-zA-Z0-9@:%_\+.~#()?&//=]*)/` |
| `!regurl?`   | http(s) 协议的可选的URL`/(https?:\/\/)?(www\.)?[-a-zA-Z0-9@:%._\+~#=]{2,256}\.[a-z]{2,6}\b([-a-zA-Z0-9@:%_\+.~#?&//=]*)/` |
| `!regcnc`   | 汉字 `/^[\u4e00-\u9fa5]{0,}$/`|
| `!regpwluns`   | 强密码,必须包含小写字母(w) ,大写字母(u),数字(n),特殊字符(s),8个字符以上 `/(?=(.*[0-9]))(?=.*[\!@#$%^&*()\\[\]{}\-_+=~`|:;"'<>,./?])(?=.*[a-z])(?=(.*[A-Z]))(?=(.*)).{8,}/` |
| `!regpwlun`   | 中等密码,必须包含小写字母(w) ,大写字母(u),数字(n),8个字符以上`/(?=(.*[0-9]))((?=.*[A-Za-z0-9])(?=.*[A-Z])(?=.*[a-z]))^.{8,}$/`|

> 未完待续
