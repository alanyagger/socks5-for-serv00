# socks5-for-serv00


### nohup模式
```bash
bash <(curl -s https://raw.githubusercontent.com/cmliu/socks5-for-serv00/main/install-socks5.sh)
```
----
### ~pm2模式~
- ~一键安装~

~`bash <(curl -s https://raw.githubusercontent.com/cmliu/socks5-for-serv00/pm2/install-socks5.sh)`~


- 一键卸载pm2
```bash
pm2 unstartup && pm2 delete all && npm uninstall -g pm2
```
----
## Github Actions
添加 Secrets.`ACCOUNTS_JSON` 变量
```json
[
  {"username": "", "password": "", "panel": "panel4.serv00.com", "ssh": "s4.serv00.com"},
  {"username": "", "password": "", "panel": "panel7.serv00.com", "ssh": "s7.serv00.com"},
  {"username": "", "password": "", "panel": "panel.ct8.pl", "ssh": "s1.ct8.pl"}
]
```

