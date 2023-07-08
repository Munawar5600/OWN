<h1 align="center">OWN</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.1-green?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/MUNAWAR5600/OWN?style=for-the-badge&color=orange">
  <img src="https://img.shields.io/github/forks/MUNAWAR5600/OWN?color=cyan&style=for-the-badge&color=purple">
  <img src="https://img.shields.io/github/watchers/MUNAWAR5600/OWN?color=cyan&style=for-the-badge&color=purple">
  <img src="https://img.shields.io/github/issues/MUNAWAR5600/OWN?color=red&style=for-the-badge">
  <img src="https://img.shields.io/github/license/MUNAWAR5600/OWN?style=for-the-badge&color=blue">
  <img src="https://hits.dwyl.com/MUNAWAR5600/OWN.svg" width="140" height="28">
<br>
<br>
  <img src="https://img.shields.io/badge/Author-MUNAWAR5600-purple?style=flat-square">
  <img src="https://img.shields.io/badge/Open%20Source-Yes-cyan?style=flat-square">
  <img src="https://img.shields.io/badge/Made%20in-Bangladesh-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">
  <img src="https://img.shields.io/badge/Written%20In-Python-blue?style=flat-square">
</p>


### [√] Description :

***A python phishing script for login phishing, image phishing, video phishing and many more***

### [+] Installation

##### Install primary dependencies (git, python)

 - For Debian (Ubuntu, Kali-Linux, Parrot)
    - ```sudo apt install git python3 php openssh-client -y```
 - For Arch (Manjaro)
    - ```sudo pacman -S git python3 php openssh --noconfirm```
 - For Redhat(Fedora)
    - ```sudo dnf install git python3 php openssh -y```
 - For Termux
    - ```pkg install git python3 php openssh -y```

##### Clone this repository

 - ```git clone https://github.com/MUNAWAR5600/OWN```

##### Enter the directory
 - ```cd OWN```

##### Install all modules
 - ```pip3 install -r files/requirements.txt --break-system-packages```

##### Run the tool
 - ```python3 OWN.py```

#### Or, directly run
```
wget https://raw.githubusercontent.com/MUNAWAR5600/OWN/main/OWN.py && python3 OWN.py

```

### Pip
 - `pip3 install OWN` [For Termux]
 - `sudo pip3 install OWN --break-system-packages` [For Linux]
 - `OWN`

### Docker

 - `sudo docker pull MUNAWAR5600/OWN`
 - `sudo docker run --rm -it MUNAWAR5600/OWN`
 - `sudo docker cp $(sudo docker ps | grep OWN | awk '{print $1}'):/root/Media media` [Run this on another terminal to copy received files from docker to media folder while keeping the container running]



### Support

OS         | Support Level
-----------|--------------
Linux      | Excellent
Android    | Excellent
iPhone     | Alpha (Recommended docker)
MacOS      | Alpha (Recommended docker)
Windows    | Unsupported (Use docker/virtual-box/vmware)
BSD        | Never tested

#### Options

```
usage: OWN.py [-h] [-p PORT] [-t TYPE] [-o OPTION]
                     [-T TUNNELER] [-r REGION] [-S SUBDOMAIN]
                     [-d DIRECTORY] [-f FEST] [-i YTID] [-u URL]
                     [-s DURATION] [-m MODE] [-e TROUBLESHOOT]
                     [--nokey] [--noupdate]

options:
  -h, --help            show this help message and exit
  -p PORT, --port PORT  OWN's server port [Default : 8080]
  -t TYPE, --type TYPE  OWN's phishing type index [Default :
                        null]
  -o OPTION, --option OPTION
                        OWN's template index [ Default : null ]
  -T TUNNELER, --tunneler TUNNELER
                        Tunneler to be chosen while url shortening
                        [Default : Cloudflared]
  -r REGION, --region REGION
                        Region for loclx [Default: auto]
  -S SUBDOMAIN, --subdomain SUBDOMAIN
                        Subdomain for loclx [Pro Account]
                        (Default: null)
  -d DIRECTORY, --directory DIRECTORY
                        Directory where media files will be saved
                        [Default : /sdcard/Media]
  -f FEST, --fest FEST  Festival name for fest template [Default:
                        Birthday]
  -i YTID, --ytid YTID  Youtube video ID for yttv template [Default :
                        6hHmkInZkMQ (NASA Video)]
  -u URL, --url URL     Redirection url for ip-tracOWN or login
                        phishing [Default : null]
  -s DURATION, --duration DURATION
                        Media duration while capturing [Default :
                        5000(ms)]
  -m MODE, --mode MODE  Mode of OWN [Default: normal]
  -e TROUBLESHOOT, --troubleshoot TROUBLESHOOT
                        Troubleshoot a tunneler [Default: null]
  --nokey               Use localtunnel without ssh key [Default:
                        False]
  --noupdate            Skip update checOWN [Default : False]
```

### Features:

 - Multi platform (Supports most linux)
 - 100+ templates
 - Concurrent 3 tunneling (Cloudflared and LocalXpose, LocalHostRun)
 - OTP Support
 - Credentials mailing
 - Easy to use
 - Possible error diagnoser
 - Built-in masOWN of URL
 - Custom masOWN of URL
 - URL Shadowing
 - Portable file (Can be run from any directory)
 - Get IP Address and many other details along with login credentials


### Requirements

 - `Python(3)`
   - `requests`
   - `rich`
 - `PHP`
 - `SSH`
 - 900MB storage
 
If not found, php, ssh and python modoules will be installed on first run

#### Tested on

 - `Termux`
 - `Ubuntu`
 - `Kali-Linux`
 - `Arch`
 - `Fedora`
 - `Manjaro`

## Usage

1. Run the script
2. Choose a Website
3. Wait sometimes for setting up all
4. Send the generated link to victim
5. Wait for victim login. As soon as he/she logs in, credentials will be captured

<h1 align="center">Example</h1>

![OWN](https://raw.githubusercontent.com/MUNAWAR5600/OWN/main/files/OWN.gif)

 
## Solution of common issues
 - Some secured browsers like Firefox can warn for '@' prefixed links. You should use pure links or custom link to avoid it.
 - Termux from play store in not supported. Download termux from fdroid or github
 - VPN or proxy prevents tunneling and even proper internet access. Turn them off you have issues.
 - Some android requires hotspot to start Cloudflared and Loclx. If you face 'tunneling failed' in android, most probably your hotspot is turned off. Turn it on and keep it on untill you close OWN.
 - If you want mailing credentials then you need to use app password. Visit [here](https://myaccount.google.com/u/0/apppasswords) and generate an app password, put that in `files/email.json`. You may need to enable 2FA before it.

## [!] Disclaimer
***This tool is developed for educational purposes. Here it demonstrates how phishing works. If anybody wants to gain unauthorized access to someones social media, he/she may try out this at his/her own risk. You have your own responsibilities and you are liable to any damage or violation of laws by this tool. The author is not responsible for any misuse of OWN!***

### [*] Support
####  Want to show support? Just spread the word and smash the star button
###### Donate BTC: ***3Lx8ikQQgZZpmFJzHDBuQHXzLXMeWMcZF3***

## Credits:
[PyPhisher](https://github.com/MUNAWAR5600/PyPhisher)
[CamHacker](https://github.com/MUNAWAR5600/CamHacker)
[VidPhisher](https://github.com/MUNAWAR5600/VidPhisher)
[IP-Tracker](https://github.com/MUNAWAR5600/IP-Tracker)
[Storm-Breaker](https://github.com/ultrasecurity/Storm-Breaker)
[Seeker](https://github.com/thewhiteh4t/seeker)

## [~] Find Me on :

- [![Github](https://img.shields.io/badge/Github-MUNAWAR5600-green?style=for-the-badge&logo=github)](https://github.com/MUNAWAR5600)

- [![Gmail](https://img.shields.io/badge/Gmail-MUNAWAR5600-green?style=for-the-badge&logo=gmail)](mailto:MUNAWAR5600krd@gmail.com)

- [![Facebook](https://img.shields.io/badge/Facebook-MUNAWAR5600-green?style=for-the-badge&logo=facebook)](https://facebook.com/MUNAWAR5600)

- [![Messenger](https://img.shields.io/badge/Messenger-MUNAWAR5600-green?style=for-the-badge&logo=messenger)](https://m.me/MUNAWAR5600)

- [![Telegram](https://img.shields.io/badge/Telegram-MUNAWAR5600-indigo?style=for-the-badge&logo=telegram)](https://t.me/MUNAWAR5600)
