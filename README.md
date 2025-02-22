# EVPN Lab

Thank you for following along on the EVPN Blog post series on <https://mikelossmann.me>. This is the repository for the blog and video series! Every time a new blog post and YouTube video is uploaded this repo will be updated to reflect the starting configuratino and the ending configuation for that post and video.

## Lab Basics

> [!IMPORTANT]
> I will _NOT_ supply any of the networking device images used. You must use images that you are licensed to use.

- This lab is built in eve-ng, I have provided a topology file which is in /Configurations/EVPN Lab - Base Configuration.zip
- Management interfaces are configured with DHCP and their is a default route present for my management network
- The credentials for the devices are all the same
  - username: _admin_
  - password: P@55w0rd!
- Management interface are set for DHCP and are in the _management_ VRF
- There is a file at the root of this folder called [IPAddresses.csv](/IPaddresses.csv) where I have all the addresses for this lab.
- The Linux image that I have used is located here: <https://bit.ly/3V4lGNG>
  - The username is root and the password is eve

## Lab Sections, with links to Blog

|      Lab       | Blog Link |
| :------------: | :-------: |
|[OSPF](/Configurations/OSPF/README.md)      |   <https://bit.ly/4juIW20>        |
|[Multicast](/Configurations/Multicast/README.md)  |  <https://bit.ly/40KMFRQ>         |
|[BGP](/Configurations/BGP/README.md)        | <https://bit.ly/4hCEFrQ>          |
|[VXLAN-and-EVPN](/Configurations/VXLAN-and-EVPN/README.md)  |  <https://bit.ly/4ghyAzH>         |
