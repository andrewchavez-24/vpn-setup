<p align="center">
<img src="https://i.imgur.com/MntON5Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h1>How to Setup and Use a VPN</h1>

This tutorial covers the prerequisites and installation process for setting up and using a VPN.<br />

<h2>Environments and Technologies Used</h2>

- A VPN (Proton VPN)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>

<h3>Create Virtual Machine in Azure</h3>

<br>
<p>FROM YOUR OWN MACHINE, browse to https://whatismyipaddress.com and take note of this in a text file</p>  
<br/>
<p>
  <img src="https://github.com/user-attachments/assets/9aa9ebec-41da-4711-8349-40c161b60e60" height="80%" width="80%"/>
</p>

<br>
<p>Create a VM in Azure</p>
<p>
<img src="https://github.com/user-attachments/assets/7e7f9460-f4df-4227-b0ab-7815c51ce8e4" height="80%" width="80%"/>
</p>

<br>
<p>Log in to the VM using Remote Desktop</p>
<p>
<img src="https://github.com/user-attachments/assets/b34ff14c-021b-41b6-95d1-d67094b7581d" height="80%" width="80%"/>
</p>

<br>
<p>FROM THE VIRTUAL MACHINE, browse to https://whatismyipaddress.com and take note of this in a text file</p>
<p>
<img src="https://github.com/user-attachments/assets/eda11f7a-f22c-4e69-9c38-9409791363aa" height="80%" width="80%"/>
</p>

<br>
<h3>Sign up for ProtonVPN and test the VPN connection</h3>
<p>On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en </p>
<br>
<p>Back within your VM, download the Proton VPN client</p>
<p>
  <img src="https://github.com/user-attachments/assets/197237e7-26b3-493d-bfbf-4c600ae889c7" height="80%" width="80%"/>
</p>

<br>
<p>Login to the VPN application and click Quick Connect</p>
<p>
<img src="https://github.com/user-attachments/assets/ce003641-6a97-429c-9c41-e3f724e836ad" height="80%" width="80%" alt="Setting Up in Azure"/>
</p>

<br>
<p>Browse to https://whatismyipaddress.com/  and observe the new IP Address and Location that you are now browsing from.</p>
<p>
<img src="https://github.com/user-attachments/assets/a50f279b-7ac4-4d47-9bec-1784d0f54b5d" height="80%" width="80%" alt="Setting Up in Azure"/>
</p>


<h2>Proton VPN is now set up!</h2>

<b> We've successfully downloaded, installed, and used a free VPN called ProtonVPN! We observed all of the different changes that happened with our IP address and location.</b>

