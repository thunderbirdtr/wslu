<div align="center">

<img width="150" height="150" src="extras/icon.png">

# wslu - 一套Windows 10 Linux子系統工具組

[![GitHub license](https://badgen.net/github/license/wslutilities/wslu?icon=github&label=&color=cyan)](https://github.com/wslutilities/wslu/blob/master/LICENSE)
[![GitHub (pre-)release](https://badgen.net/github/release/wslutilities/wslu?icon=github&label=&color=yellow)](https://github.com/wslutilities/wslu)
[![Circle CI master](https://badgen.net/circleci/github/wslutilities/wslu/master?label=master&icon=circleci)](https://circleci.com/gh/wslutilities/wslu/tree/master)
[![Circle CI develop](https://badgen.net/circleci/github/wslutilities/wslu/develop?label=develop&icon=circleci)](https://circleci.com/gh/wslutilities/wslu/tree/develop)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fpatrick330602%2Fwslu.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fpatrick330602%2Fwslu?ref=badge_shield)
[![Donate](https://badgen.net/badge/Donate/Paypal/purple)](https://www.paypal.me/callmepk/)

[English](README.md) | [简体中文](README.hans.md) | 繁體中文

</div>

這是一套適用於Windows 10 Linux子系統的工具組，可以在Windows 10 Linux子系統下完成諸如將Windows路徑轉換為WSL專屬路徑或者建立你最喜愛的Linux程式桌面快捷方式等工作。需要Windows 10創造者更新或更高。

**目前支援的Linux發行版：**
- Ubuntu
- Ubuntu 16.04
- Ubuntu 18.04
- OpenSUSE
- SUSE Linux Enterprise Server (SLES)
- Debian GNU/Linux
- Kali Linux
- [WLinux](https://afflnk.microsoft.com/c/1291904/433017/7593?u=https%3A%2F%2Fwww.microsoft.com%2Fstore%2FproductId%2F9NV1GV1PXZ6P)

舊版Ubuntu不再被支援。

## 功能

**wslusc**
這是用於建立Linux程式Windows桌面捷徑的工具。

**wslsys**
這是可以展示Windows和Linux下的系統資訊的工具。

**wslfetch**
這是類似於screenfetch的系統資訊展示工具。

**wslupath**
這是用於轉換Windows/WSL路徑的工具。

**wslview**
這是一個將Windows預設網路瀏覽器繫結為WSL網路瀏覽器的包裝工具。

## 安裝

### WLinux

WLinux已內建。

### Ubuntu/Debian/Kali Linux

執行以下命令:
```bash
sudo apt install apt-transport-https
wget -O - https://api.patrickwu.ml/public.key | sudo apt-key add -
echo "deb https://apt.patrickwu.ml/ stable main" | sudo tee -a /etc/apt/sources.list 
sudo apt update
sudo apt install wslu
```

或者你可以從Releases介面下載.deb進行安裝：`sudo dpkg -i wslu*`。

### OpenSUSE/SLES

執行以下命令:執行以下命令:
```bash
sudo zypper ar https://rpm.patrickwu.ml/ ruapm
sudo zypper ref
sudo zypper in wslu
```

或者你可以從Releases介面下載.rpm進行安裝：`sudo rpm -ivh "wslu*"`。

## 貢獻（英文）

請檢視[CONTRIBUTING.md](CONTRIBUTING.md)。

## 行為守則（英文）

請檢視[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)。

## 後記

發現過了100個star也沒加中文README。。。反而給[隔壁項目](https://afflnk.microsoft.com/c/1291904/433017/7593?u=https%3A%2F%2Fwww.microsoft.com%2Fstore%2FproductId%2F9NV1GV1PXZ6P)加了中文README，給自己扇幾個耳光先(￣ε(#￣)☆╰╮o(￣皿￣///)

做項目不易，請我喝杯咖啡唄 (*´﹃\`)
| 微信支付 | 支付寶 |
| :-------: | :-----: |
| <img width="300" height="300" src="https://patrickwu.ml/images/base/wechatpay.jpg"> | <img width="300" height="300" src="https://patrickwu.ml/images/base/alipay.jpg"> |

## 許可（英文）

<pre>
This is free software; you can redistribute it and/or modify
it under the terms of the GNU GPL version 3 or (at your option) any later version.
There is NO warranty; not even MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
</pre>

更長版本請檢視[LICENSE](LICENSE)。

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fpatrick330602%2Fwslu.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fpatrick330602%2Fwslu?ref=badge_large)
