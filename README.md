# Virtual-Lab
My virtual lab that I built to build knowledge and better understand what sort of infrastructure IT support works with
https://www.youtube.com/watch?v=MHsI8hJmggI&t=3591s mostly following this video by Josh Madakor

Technologies: VirtualBox, Windows Server, Windows 10, Active Directory, DHCP, NAT, RAS, PowerShell

 i built my virtual machine


and then i configured the internet connections for my internal network and the network on myhost pc for it

i configured user roles by configuring active directory in domain. 

i upgraded this active directory to a domain meaning


I then created an organization unit and added a user(myself admin), i added roles 

 added roles for my admin to remote connect

i configured the neat netword address translation and an ras
as well as a dhcp server, i added ip addresses scope for users within the vm. And it seems like that works for ipv4 and ipv6

i used a script that i found through the online series i was referencing to add my online users


Setup another client virtual network and chose the interneal networrk to have it use the DHCP that i setup


Setup another thing with a thing and had it be the user with windows 10 iso not server. Used ipconfig. there was no default gateway


set it up in domain controller, pinged domain and google .and got a response

I then tried to join the server as another user, I found that my default configuration was not set as my domain controllers and managed that.

I joined in as my user account, and pinged my domain successfully
