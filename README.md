# Get Ubuntu x86_64 on your terminal/termux via ssh
1) Register your account on ngrok.com
2) Login to your account and get/copy Authtoken(authentication token) in
   "Setup & Installation" option 
3) fork this repo (https://github.com/mjuned47/GHActions_SSH)
4) Now go to your repository settings and go to secrets
5) Add the following secrets :

6) after adding secrets , go to actions , select workflow (ubuntu-ssh) and run it 
7) wait for some seconds ,you will see message like
   "ssh runner@x.tcp.ngrok.io -p xxxxx"
8) copy this and open termux/terminal and install openssh
    For termux : apt update && apt install openssh
9) Paste it !
 
