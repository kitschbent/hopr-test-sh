# hopr-test-sh

nothing apart from personal tests.  probably not interesting to you in the slightest...

## install_run_vanilla instructions:

log in to vps

* wget https://github.com/kitschbent/hopr-test-sh/releases/download/v0/install_run_vanilla.sh
* chmod +x install_run_vanilla.sh
* ./install_run_vanilla.sh

### if users need to save logs

in the *local* computer:

* scp `<username>`@`<ip address>`:/hopr-chat/log.txt ~/Desktop

`<username>` is the vps username, probably `root`

`<ip address>` is the vps ip address

they will be prompted to enter the vps password and then download will begin
