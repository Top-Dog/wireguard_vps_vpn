# wireguard_vps_vpn
## Modfied for AWS EC2 and the yum package manager
Wireguard Installation Scripts 

these scripts can be used to install wireguard on a virtual private server (VPS), i.e.
a server that you have running in the cloud. They must be run as root, or switch to root with `$ sudo -i`

*Remember to open TCP/UDP Port 51820 on the VPS (listening port)*

Alternatively you can use it to install wireguard VPN software on an Amazon Linux 2 VM (offered as part of their free tier).

There is an installation script called wireguard.sh that does all the necessary things for you in order to install wireguard on the virtual server.

A second script called addpeer.sh can be used to add an additional client or peer, such as a laptop running windows or an iPhone.

I have designed the scripts in a way that you can either transfer them over to the server as a file and call them from the command line or – alternatively – you can copy and paste the content directly into the terminal window.

Find all details on [my youtube channel](https://www.youtube.com/channel/UCG5Ph9Mm6UEQLJJ-kGIC2AQ)

If you are having issues with these scripts (they don't work as expected etc.) then you may join my discord server and chat life with me - please see [THIS VIDEO](https://youtu.be/VouCBt1NTjw) for details
