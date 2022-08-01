# 💎 Phish4Get 💎
_Phish4Get is an easy to use phishing tool with over 70+ website templates. Author is not responsible for any misuse!_


### [✔️] Description :
Phish4Get is a ultimate phishing tool in python including popular websites like facebook, twitter, instagram, github, reddit, gmail and many others.

### [+] Installation:
Install primary dependencies (git, python, php)

##### For Debian (Ubuntu, Kali-Linux, Parrot)
`sudo apt install git python php -y`

##### For Arch (Manjaro)
`sudo pacman -S git python php`

##### For Redhat(Fedora)
`sudo dnf install git python php -y`

##### For Termux
`pkg install git python php -y`

#### Clone This Repository
`git clone https://github.com/talhazmedia/Phish4Get`

##### Enter The Directory
`cd Phish4Get`

##### Install All Modoules
`pip3 install -r requirements.txt`

##### Run the tool
`python3 phish4get.py`

#### Or, directly run
`wget https://raw.githubusercontent.com/talhazmedia/Phish4Get/main/phish4get.py && python3 phish4get.py`

### Pip:
`pip3 install phish4get` [For Termux]
`sudo pip3 install phish4get` [For Linux]
`phish4get`

### Docker:
`sudo docker pull talhazmedia/phish4get`
`sudo docker run --rm -it talhazmedia/phish4get`

### Options:
```
usage: phish4get.py [-h] [-p PORT] [-o OPTION] [-t TUNNELER] [--noupdate]
  -h, --help            show this help message and exit
  -p PORT, --port PORT  Phish4Get's server port [ Default : 8080 ]
  -o OPTION, --option OPTION
                        Phish4Get's template index [ Default : null ]
  -t TUNNELER, --tunneler TUNNELER
                        Tunneler to be chosen while url shortening
  --noupdate            Skip update checking
```

😉 Features:
* Multi platform (Supports most linux)
* 77 Website templates
* Concurrent triple tunneling (Ngrok, Cloudflared and Loclx)
* OTP Support
* Credentials mailing
* Easy to use
* Possible error diagnoser
* Built-in masking of URL
* Custom masking of URL
* URL Shadowing
* Portable file (Can be run from any directory)
* Get IP Address and many other details along with login credentials
* Relevant Tools by Me

### Requirements
1. Python(3)
2. requests
3. bs4
4. PHP
5. 200MB storage
_If not found, php and python modoules will be installed on first run_

## Tested on:
* Termux
* Ubuntu
* Kali-Linux
* Arch
* Fedora
* Manjaro
### Usage
1. Run the script
2. Choose a Website
3. Wait sometimes for setting up all
4. Send the generated link to victim
5. Wait for victim login. As soon as he/she logs in, credentials will be captured. 
