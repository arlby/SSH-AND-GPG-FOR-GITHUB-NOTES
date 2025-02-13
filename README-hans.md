# SSH AND GPG FOR GITHUB NOTES

[EN](/README.md)| 中文

## Git 的安装

```
https://git-scm.com/
```

## 密钥生成

ssh-keygen -t rsa -b 4096 -C "xxx@users.noreply.github.com"  
其中RSA 是加密类型 4096是加密位数 例如 2048 1024  

把生成的public key添加到Github

## 连接
```
ssh -T git@github.com
```