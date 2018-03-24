# SIM7100-dial-script

## 存在问题

修改了noauth项   18.3.24
对应pppd拨号时出现pap或者chap需要authorization的时候报错

## 使用方法
Located in /etc/ppp/


```
├── **gprs-connect-chat**
├── peers
│   ├── **gprsdial**
│   └── **gprsdial2**
└── resolv.conf
```

Call:

```
sudo pppd call gprsdial
sudo pppd call gprsdial2
```
