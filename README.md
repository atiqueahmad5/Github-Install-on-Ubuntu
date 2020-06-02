# Github-Install-on-Ubuntu
Debian/Ubuntu distributions
To setup the package repository, run these commands:

$ wget -qO - https://packagecloud.io/shiftkey/desktop/gpgkey | sudo apt-key add -


$ sudo sh -c 'echo "deb [arch=amd64] https://packagecloud.io/shiftkey/desktop/any/ any main" > /etc/apt/sources.list.d/packagecloud-shiftky-desktop.list'


$ sudo apt-get update


Then install GitHub Desktop:

$ sudo apt install github-desktop
