## Git installation

```
https://git-scm.com/
```

## Key generation

ssh-keygen -t rsa -b 4096 -C "xxx@users.noreply.github.com"
RSA is the encryption type and 4096 is the number of encryption bits, for example 2048 1024

Add the generated public key to Github

## Connection
```
ssh -T git@github.com
```