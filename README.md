# hopr-test-sh

nothing apart from personal tests.  probably not interesting to you in the slightest...

## install-uni instructions:

log in to vps

* wget https://github.com/kitschbent/hopr-test-sh/releases/download/v0.3/install-uni.sh
* chmod +x install-uni.sh
* ./install-uni.sh

### to run chat in local browser

* ssh -L 3000:0.0.0.0:3000 root@`<ip address of VPS>`
* you'll then be prompted to enter your password

### if users need to save logs primitively

in the *local* computer:

* scp `<username>`@`<ip address>`:/hopr-chat/log.txt ~/Desktop

`<username>` is the vps username, probably `root`

`<ip address>` is the vps ip address

they will be prompted to enter the vps password and then download will begin
