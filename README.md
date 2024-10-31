<h1 align="center">$$\color{#a5a5a5} \Large \text{BPB PANEL}$$</h1>

 __*[🇮🇷 Persian](README-fa.md)*__
 __*[🇬🇧 English](README.md)*__

<p align="center">
  <img src="https://github.com/user-attachments/assets/2687f318-87eb-4af6-a30a-5904f25bd394" width="160px" 
   style="text-align: center;" alt="https://github/.com/NiREvil/bia-pain-bache"<figcaption> v2.7
</p><br>


<h2>$$\color{#a5a5a5} \Large \text{Table of Contents}$$</h2>

- [Introduction](#Introduction)
- [Features](#Features)
- [How to use](#How-to-use)
- [Variable description](#Variable-description)
- [Panel preview](#Panel-preview)  
- [Supported clients](#Supported-clients)

<br><br>

<h2>$$\color{#a5a5a5} \Large \text{Introduction}$$</h2>

#### $$\color{gray} \large \text{This project is dedicated to developing a user panel for the Cloudflare Workers-Pages proxy-script created by}$$ $$\color{gold} \Large \text{yonggekkk}$$ [^1] 
#### $$\color{gray} \large \text{Huge thanks to}$$ $$\color{gold} \Large \text{Bia Pain Bache}$$ [^2] $$\color{gray} \large \text{for creating these amazing panel}$$
<br><br>

<h3>$$\color{#a5a5a5} \Large \text{The panel offers two deployment options:}$$</h3>

> [Worker __deployment__](docs/worker_installation_fa.md)  
> [Pages __deployment__](docs/pages_installation_fa.md)
<br><br>

## Features

1. **Free**: No cost involved.
2. **User-Friendly Panel:** Designed for easy navigation, configuration and usage.
3. **Protocols:** Provides VLESS, Trojan and Wireguard (Warp) protocols.
4. **Warp Pro configs:** Optimized Warp for crucial circumstances.
5. **Support Fragment:** Supports Fragment functionality for crucial network situations.
6. **Full routing rules:** Bypassing Iran/China/Russia and LAN, Blocking QUIC, Porn, Ads, Malwares, Phishing...
7. **Chain Proxy:** Capable of adding a chain proxy to fix IP.
8. **Supports Wide Range of Clients:** Offers subscription links for Xray, Sing-box and Clash core clients.
9. **Password-Protected Panel:** Secure your panel with password protection.
10. **Fully customizable:** Ability to use online scanner and setting up clean IP-domains, Proxy IP, setting DNS servers, choosing ports and protocols, Warp endpoints...
<br>

## How to use
- [Installation (Pages)](docs/pages_installation_fa.md)
- [Installation (Worker)](docs/worker_installation_fa.md)
- [Scanning Proxy IP](docs/proxy-ip-scanner.md)
- [How to use](docs/configuration_fa.md)
- [FAQ](docs/faq.md)
<br>

## Variable description
> For further information on how to create variables, please refer to [this link](https://github.com/NiREvil/bia-pain-bache/blob/main/docs/pages_installation_fa.md#3--%D8%AA%D8%BA%DB%8C%DB%8C%D8%B1-%D9%BE%D8%B3%D9%88%D8%B1%D8%AF%D9%87%D8%A7%DB%8C-trojan).

![rainbow](https://github.com/NiREvil/vless/assets/126243832/1aca7f5d-6495-44b7-aced-072bae52f256)
| Variable Name | Example | Required | Remark |
|-----|----|--|------------|
| UUID | `90cd4a77-141a-43c9-991b-08263cfe9c10` |✅| To generate your own UUID refer to [this link](https://www.uuidgenerator.net/) |
| PROXYIP | `bpb.radically.pro` |❌| Alternative as a proxy node for accessing CloudFlareCDN site (supports multiple ProxyIPs, ex: ```['bpb.radically.pro', 'bpb.yousef.isegaro.com'];``` To find proxyIP [check here](https://github.com/NiREvil/vless/blob/main/sub/ProxyIP.md) |
| TROJAN_PASS  | `REvil` |✅| Your preferred password |
| HASH_PASS | `6dfd0e8e67ad3230498f80938cb924bc767b7` |✅| Your preferred trojan password should be converted to SHA-224 Hash string to securely store password and verify data integrity, To perform this conversion refer to [this link](https://emn178.github.io/online-tools/sha224.html) |

![rainbow](https://github.com/NiREvil/vless/assets/126243832/1aca7f5d-6495-44b7-aced-072bae52f256)

## Panel preview

<p align="center">
  <img src="docs/assets/images/Panel.png">
</p>

<p align="center">
  <img src="docs/assets/images/Panel_2.png">
</p>

<p align="center">
  <img src="docs/assets/images/Panel_3.png">
</p>

<p align="center">
  <img src="docs/assets/images/Panel_4.png">
</p>

<p align="center">
  <img src="docs/assets/images/Panel_5.png">
</p>

<p align="center">
  <img src="docs/assets/images/Panel_6.png">
</p>

<br><br> 

<br><br>

## Supported clients  

| Client  | Version | Fragment | Warp Pro |
| :-------------: | :-------------: | :-------------: | :-------------: |
| __v2rayNG__  | 1.8.19 or higher  | :heavy_check_mark: | :x: |
| __v2rayN__  | 6.42 or higher  | :heavy_check_mark: | :x: |
| __v2rayN-PRO__  | 1.4 or higher  | :heavy_check_mark: | :heavy_check_mark: |
| __Nekobox__  |   | :x: | :x: |
| __Sing-box__  | 1.8.10 or higher  | :x: | :x: |
| __Streisand__  |   | :heavy_check_mark: | :x: |
| __V2Box__  |   | :x: | :x: |
| __Shadowrocket__  |   | :x: | :x: |
| __Nekoray__  |   | :heavy_check_mark: | :x: |
| __Hiddify__  | 2.0.5 or higher  | :x: | :heavy_check_mark: |
| __NikaNG__  |   | :heavy_check_mark: | :heavy_check_mark: |
| __Clash Meta__  |   | :x: | :x: |
| __Clash Verge Rev__  |   | :x: | :x: |
| __FLClash__  |   | :x: | :x: |

---

### Special Thanks
- CF-vless code author [3Kmfi6HP](https://github.com/3Kmfi6HP/EDtunnel)
- CF preferred IP program author [badafans](https://github.com/badafans/Cloudflare-IP-SpeedTest), [XIU2](https://github.com/XIU2/CloudflareSpeedTest)
---

- For a detailed tutorial on the core script, please refer to [Yongge’s blog and video tutorials](https://ygkkk.blogspot.com/2023/07/cfworkers-vless.html).
---

[^1]: [yonggekkk](https://github.com/yonggekkk/Cloudflare-workers-pages-vless) 
[^2]: [BPB](https://github.com/bia-pain-bache) 
