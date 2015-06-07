DESCRIPTION
This repo contains no code of mine.

It is a merge of the original hostapd sources from
https://github.com/bartve-enovation/hostap.git

pritambaral fixes for the Realtek driver 8192cu
https://github.com/pritambaral/hostapd-rtl871xdrv

openwrt noscan fix, taken from jekader:
https://github.com/jekader/hostapd-rtl.git


LICENSE
refer to the above mentioned repos

TO BUILD
clone the repo
checkout the branch 'bpir1'
cd hostapd
make
copy the hostapd and hostapd_cli to /usr/bin 

an example of configuration file is included:
hostapd/hostapd.conf
