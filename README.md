<!DOCTYPE html>
<h2 align="center">
<hr>
Autoscript Websocket Multiport XRAY TLS/XTLS
<h2><hr>
  
<h2 align="center"> ♦️Supported Linux Distribution♦️</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"width="400"></p>
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=blue"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=18.04 LTS&color=blue"></p>
  
<p align="center"><img src="https://img.shields.io/badge/Service-Multiport (XRAY)-orange"></p>


  
## ⏩ AUTOSCRIPT WEBSOCKET LITE DETAILS ⏪
<b>
[ XRAY SERVICES ] <br>
<br>
✅ XRAY VMESS WEBSOCKET TLS & NON-TLS <br>
✅ XRAY VLESS WEBSOCKET TLS & NON-TLS <br>
✅ XRAY TROJAN WEBSOCKET TLS & NON-TLS <br>
✅ XRAY VMESS GRPC <br>
✅ XRAY VLESS GRPC <br>
✅ XRAY TROJAN GRPC <br>
<br>
[ OTHER SERVICES ] <br>
<br>
✅ YAML LINK <br>
✅ DNS CHANGER <br>
✅ AUTOSCRIPT UPDATE <br>
✅ NETFLIX REGION CHECKER <br>
✅ CHECK LOGIN USER <br>
✅ CHECK CREATED CONFIG <br>
✅ AUTOMATIC CLEAR LOG <br>
✅ AUTOMATIC VPS REBOOT <br>
✅ BACKUP & RESTORE <br></br>


### How to install:

1. Create VPS using any cloud provider you prefer
2. Register domain from any domain registrar
3. Set DNS Records from your domain registrar to VPS public IP
4. Wait until it takes effect
5. Run below commands:

#### For Debian 10 Only For First Time Installation
```bash
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
```

#### For Ubuntu 18.04 Only For First Time Installation
```bash
apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot
```

#### Then run:
```bash
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://github.com/akbarhps/XRAYAutoscriptinstallWebsocket/raw/main/setup-lite.sh && chmod +x setup-lite.sh && ./setup-lite.sh
```

6. If all steps above has succeed, Open Cloudflare and register your domain by setting your DNS Records to:

```
Type | Name | Content   | Proxy status | TTL
A    | @    | Public IP | DNS Only     | Auto
```

7. Set your Domain Registrar `Nameservers` to `Cloudflare Nameservers`
8. In Cloudflare, go to SSL/TLS tab and set `Your SSL/TLS encryption mode` to `Full` and enable `SSL/TLS Recommender`
9. In Cloudflare, go to `Network`, scroll to `Network` section and enable `gRPC` and wait few minutes until it takes effect
