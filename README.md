<h1 align="center">KING</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.1-green?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/Munawar/KING?style=for-the-badge&color=orange">
  <img src="https://img.shields.io/github/forks/Munawar/KING?color=cyan&style=for-the-badge&color=purple">
  <img src="https://img.shields.io/github/watchers/Munawar/KING?color=cyan&style=for-the-badge&color=purple">
  <img src="https://img.shields.io/github/issues/Munawar/KING?color=red&style=for-the-badge">
  <img src="https://img.shields.io/github/license/Munawar/KING?style=for-the-badge&color=blue">
  <img src="https://hits.dwyl.com/Munawar/KING.svg" width="140" height="28">
<br>
<br>
  <img src="https://img.shields.io/badge/Author-Munawar-purple?style=flat-square">
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

 - ```git clone https://github.com/Munawar/KING```

##### Enter the directory
 - ```cd KING```

##### Install all modules
 - ```pip3 install -r files/requirements.txt --break-system-packages```

##### Run the tool
 - ```python3 KING.py```

#### Or, directly run
```
wget https://raw.githubusercontent.com/Munawar/KING/main/KING.py && python3 KING.py

```

### Pip
 - `pip3 install KING` [For Termux]
 - `sudo pip3 install KING --break-system-packages` [For Linux]
 - `KING`

### Docker

 - `sudo docker pull Munawar/KING`
 - `sudo docker run --rm -it Munawar/KING`
 - `sudo docker cp $(sudo docker ps | grep KING | awk '{print $1}'):/root/Media media` [Run this on another terminal to copy received files from docker to media folder while keeping the container running]



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
usage: KING.py [-h] [-p PORT] [-t TYPE] [-o OPTION]
                     [-T TUNNELER] [-r REGION] [-S SUBDOMAIN]
                     [-d DIRECTORY] [-f FEST] [-i YTID] [-u URL]
                     [-s DURATION] [-m MODE] [-e TROUBLESHOOT]
                     [--nokey] [--noupdate]

options:
  -h, --help            show this help message and exit
  -p PORT, --port PORT  KING's server port [Default : 8080]
  -t TYPE, --type TYPE  KING's phishing type index [Default :
                        null]
  -o OPTION, --option OPTION
                        KING's template index [ Default : null ]
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
  -u URL, --url URL     Redirection url for ip-tracking or login
                        phishing [Default : null]
  -s DURATION, --duration DURATION
                        Media duration while capturing [Default :
                        5000(ms)]
  -m MODE, --mode MODE  Mode of KING [Default: normal]
  -e TROUBLESHOOT, --troubleshoot TROUBLESHOOT
                        Troubleshoot a tunneler [Default: null]
  --nokey               Use localtunnel without ssh key [Default:
                        False]
  --noupdate            Skip update checking [Default : False]
```

### Features:

 - Multi platform (Supports most linux)
 - 100+ templates
 - Concurrent 3 tunneling (Cloudflared and LocalXpose, LocalHostRun)
 - OTP Support
 - Credentials mailing
 - Easy to use
 - Possible error diagnoser
 - Built-in masking of URL
 - Custom masking of URL
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

![KING](https://raw.githubusercontent.com/Munawar/KING/main/files/KING.gif)

 
## Solution of common issues
 - Some secured browsers like Firefox can warn for '@' prefixed links. You should use pure links or custom link to avoid it.
 - Termux from play store in not supported. Download termux from fdroid or github
 - VPN or proxy prevents tunneling and even proper internet access. Turn them off you have issues.
 - Some android requires hotspot to start Cloudflared and Loclx. If you face 'tunneling failed' in android, most probably your hotspot is turned off. Turn it on and keep it on untill you close KING.
 - If you want mailing credentials then you need to use app password. Visit [here](https://myaccount.google.com/u/0/apppasswords) and generate an app password, put that in `files/email.json`. You may need to enable 2FA before it.

## [!] Disclaimer
***This tool is developed for educational purposes. Here it demonstrates how phishing works. If anybody wants to gain unauthorized access to someones social media, he/she may try out this at his/her own risk. You have your own responsibilities and you are liable to any damage or violation of laws by this tool. The author is not responsible for any misuse of KING!***

### [*] Support
####  Want to show support? Just spread the word and smash the star button
###### Donate BTC: ***3Lx8ikQQgZZpmFJzHDBuQHXzLXMeWMcZF3***

## Credits:
[PyPhisher](https://github.com/Munawar/PyPhisher)
[CamHacker](https://github.com/Munawar/CamHacker)
[VidPhisher](https://github.com/Munawar/VidPhisher)
[IP-Tracker](https://github.com/Munawar/IP-Tracker)
[Storm-Breaker](https://github.com/ultrasecurity/Storm-Breaker)
[Seeker](https://github.com/thewhiteh4t/seeker)

## [~] Find Me on :

- [![Github](https://img.shields.io/badge/Github-Munawar-green?style=for-the-badge&logo=github)](https://github.com/Munawar)

- [![Gmail](https://img.shields.io/badge/Gmail-Munawar-green?style=for-the-badge&logo=gmail)](mailto:Munawarkrd@gmail.com)

- [![Facebook](https://img.shields.io/badge/Facebook-Munawar-green?style=for-the-badge&logo=facebook)](https://facebook.com/Munawar)

- [![Messenger](https://img.shields.io/badge/Messenger-Munawar-green?style=for-the-badge&logo=messenger)](https://m.me/Munawar)

- [![Telegram](https://img.shields.io/badge/Telegram-Munawar-indigo?style=for-the-badge&logo=telegram)](https://t.me/Munawar)
