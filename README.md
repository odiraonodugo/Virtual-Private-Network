
<p align="center">
<img src="https://github.com/odiraonodugo/image/blob/main/vpn.jpg" alt="Virtual Private Network Logo"/>
</p>



<h1>VPN - Virtual Private Network</h1>
This tutorial outlines the installation of Virtual Private Network (VPN) on Azure Virtual Machine and will be used to access site from another location .<br />



<h2>Environments and Technologies Used</h2>

 - Microsoft Azure (Virtual Machines/Compute)
 - Remote Desktop
 - Virtual Private Network (VPN)




<h2>Operating Systems Used </h2>



 - Windows 10</b> (21H2)


<h2>What is VPN?</h2>
                                                                        


VPN stands for "Virtual Private Network" and describes the opportunity to establish a protected network connection when using public networks. VPNs encrypt your internet traffic and create a tunnel and disguise your online identity. This makes it more difficult for third parties to track your activities online and steal data.

VPN are a technology that use encrypted tunnels to allow for a remote computer or network to act as if cnnected to a network that its not acturally physically connected to. In this case its used by organisations in accessing their company network in this age that we have gone remote.





![](https://github.com/odiraonodugo/image/blob/main/VPN-Tunnel.webp)
 

                       


<h2>Steps</h2>

 -  Create Virtual Machine in Azure
 -  Sign up for ProtonVPN  
 -  Test the VPN connection


<h2>Actions and Observations</h2>


Note your current IP address on a note text file by browse to [whatismyipaddress](https://whatismyipaddress.com/) on your local computer 






Create a Windows 10 Virtual Machine in another geographic location (try a different country)

![](https://github.com/odiraonodugo/image/blob/main/VM2.png)

Log into the VM with Remote Desktop

Browse to [whatismyipaddress](https://whatismyipaddress.com/) and take note of this in a text file.

You can see the IP address location.


![](https://github.com/odiraonodugo/image/blob/main/vm%20ip%20address.png)


(Sign up for ProtonVPN and test the VPN connection)

On your actual computer, sign up for the free version of Proton VPN [ProtonVPN](https://account.protonvpn.com/signup?plan=free&language=en)

Back within your VM, download the Proton VPN client

Login to the VPN and choose a VPN server in yet another country (such as Japan)


![](https://github.com/odiraonodugo/image/blob/main/vp%20connect.png)


Browse to [whatismyipaddress](https://whatismyipaddress.com/)  and take note of this in a text file.


![](https://drive.google.com/file/d/1Ufk32_IzEMDBPX21FxxV6DoaKLgDYIsl/view)



Try browsing to Google, Bing or Netflix and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different.



![](https://github.com/odiraonodugo/image/blob/main/netflix.png)



This is how you connect to VPN to access your organisational network.


![](https://github.com/odiraonodugo/image/blob/main/vpn%20connetion.png)





