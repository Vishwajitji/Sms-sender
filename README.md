# Sms-sender
RV hacker
<h1 align="center">
  <br>
  <a href="https://github.com/TheSpeedX/TBomb"><img src="https://i.ibb.co/F4HBKqm/TBomb.png" alt="TBomb"></a>
  <br>
  TBomb v2.1b
  <br>
</h1>


<p align="center">A free and open-source SMS/Call bombing application</p>

## NOTES:

#### For Termux

To use the bomber type the following commands in Termux:
```shell script
pkg install git -y 
pkg install python -y 
git clone https://github.com/TheSpeedX/TBomb.git
cd TBomb
./TBomb.sh
```

#### For iSH

To use the application, type in the following commands in iSH.
```shell script
apk add git
apk add python3
apk add py3-pip
apk add ruby
gem install toilet
git clone https://github.com/TheSpeedX/TBomb.git
cd TBomb
pip3 install -r requirements.txt
chmod +x TBomb.sh
./TBomb.sh
```

#### For Debian-based GNU/Linux distributions

To use the application, type in the following commands in GNU/Linux terminal.
```shell script
sudo apt install git
git clone https://github.com/TheSpeedX/TBomb.git
cd TBomb
bash TBomb.sh
```

#### For MacOS

To use the application, type in the following commands in MacOS terminal:

##### Install via Homebrew

```shell script
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
````

##### Install dependencies:

```shell script
brew install git
brew install python3
sudo easy_install pip
sudo pip install --upgrade pip
git clone https://github.com/TheSpeedX/TBomb.git
cd TBomb
bash TBomb.sh
```


##### Missing Tools on MacOS

The package `toilet` cannot be installed yet on macOS. But TBomb does still work.

### Demonstrative Video:

- Watch Indian Bombing Method [here](https://youtu.be/9KWkwsr_QGw)  
- Watch International Bombing Method [here](https://youtu.be/JqsHkyIcnPM).  

## Contributors

- Catch **[t0xic0der](https://github.com/t0xic0der)** at https://atlasdoc.netlify.app
- Check **[Avinash](https://github.com/AvinashReddy3108)** at https://github.com/AvinashReddy3108
- Mail **[scpketer](https://github.com/scpketer)** at scpketer@protonmail.ch
- Mail **[0n1cOn3](https://github.com/0n1cOn3)** at 0n1cOn3@gmx.ch
- Ping **Rieltar** at https://t.me/RieltarReborn
- Check **[Bishal](https://github.com/kbshal)** at https://github.com/kbshal


### Donators:

- **[34D30Y](34db0y@protonmail.com)**
- **SC AMAN**

### TODO:

- [x] Make Code More Readable and Extensible
- [ ] Add More Mail Spam APIs
- [ ] Add More SMS Spam APIs
- [ ] Add More Call Spam APIs
- [ ] Resolve threading issue in some devices

## FAQ

**Q:** Is there any TBomb Website/App ?

**A:** There is no official website/app yet.The only official releases of TBomb are published in [Github](https://github.com/TheSpeedX/TBomb) and [PyPi](https://pypi.org/project/tbomb)
##
**Q:** Poor Internet Connection Detected:

**A:** Here are a few stuff you can try:
- Check your connection.
- Make sure `openssl` is installed.
- Try to `ping` any remote site/address to be sure.
- Try to reinstall if nothing works.
##
**Q:** Do you support "X" Country?

**A:** Most Countries are supported for SMS and only India for calls. The SMS delivery rate might be different for different countries.
##
**Q:** Can you add support for "X" Country?

**A:** We do what we can, but we cannot promise. Please stay tuned for future support. If you are ready to help then maybe we can do faster.
##
**Q:** Why is the limit so low?

**A:** Due the amount of requests, the APIs can die. To prevent a bigger outtake of TBomb, it has been limited. 
##
**Q:** Help, I got the error that the requirements aren't installed, even when the installer has successfully reached the main menu

**A:** First, make sure `python3` and `pip3` are installed. 
- The Easy Method:  
   `pip3 install tbomb`  
    Then execute by simply running `tbomb`
- The Git Method:  
    Clone the repo and Switch to the TBomb Directory and execute this command:  
    `pip3 install -r requirements.txt`
##
**Q:** Help, It says `command 'tbomb' not found` after installing PIP version!

**A:** Try running `sudo pip3 install tbomb`
##
**Q:** Help, I can't execute TBomb.sh!

**A:** Run TBomb Directly with `python3 bomber.py`
##
