## Firmware of NanoPi R2S Based on Original OpenWRT

### OpenWrt Mainline supported NanoPi R2S in 28 July 2020

Release in:
https://github.com/nicksun98/R2S-OpenWrt/releases

### Noticed：
Login IP：192.168.1.1 

Password：None

The firmwares __DO NOT__ contain argon theme and material theme, JD_DailyBonus cannot be updated in Luci.  
To Update JD_DailyBonus:
```
wget --no-check-certificate https://raw.githubusercontent.com/NobyDa/Script/master/JD-DailyBonus/JD_DailyBonus.js -O /usr/share/jd-dailybonus/JD_DailyBonus.js
```
and alter `/etc/config/jd-dailybonus` version number.

To start service:
```
sh /usr/share/jd-dailybonus/app.sh
```

### Version Informations:

The Latest Edition of Snapshot （The day of the latest action）

LuCI version：19.07

Doge contains SSRP, JD-DailyBonus, UnblockNeteaseMusic

SSRP contains SSRP

### Feature：
1.O3

2.Only the most basic softwares

3.SFE supported

4.Fullcone NAT supported

5.IPv6 supported

![](/Screenshots/ss.jpeg)

## Thanks to all friends in NanoPi R2S Club
