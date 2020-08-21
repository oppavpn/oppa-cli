# OPPA Socks5 CLI 

官网登入你的账号，获取绑定 data url：

```
# data url 是 base64 編碼
oppa://foQbaFEqja....
```

绑定 URL 为第一个命令行参数：

```
./oppa oppa://foQbaFEqja...
```

如成功运行，可列表选择可用节点:

```
Routes: [la1e la1l la1k la1h la1g la1f la1d sg1 hk1 jp1 kr1 移动专用-jp2 kr2 移动专用-jp2b la4 ru1]
? Select Route:  [Use arrows to move, type to filter]
  la1e
  la1l
> la1k
  la1h
  la1g
  la1f
  la1d

Selected route: la1k
INFO[0040] listening: 127.0.0.1:1080
```

## HELP

* 可用 `-l` 选项改变本地 socks5 监听端口

```
oppa --help
usage: oppa [<flags>] <bindDataURL>

Flags:
      --help  Show context-sensitive help (also try --help-long and --help-man).
  -l, --locakSocks5Addr="127.0.0.1:1080"
              local

Args:
  <bindDataURL>  QR code data for binding service
```
