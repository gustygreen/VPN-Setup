# Vitual Private Network (VPN)
<p align="center">
<img src="https://github.com/user-attachments/assets/2a75ffe5-ab3d-4187-8ab5-6fb354582691" height="20%" width="70%"/>
</p>

<h1>VPN - Prerequisites and Installation</h1>
This tutorial covers the prerequisites and installation process for setting up and using a VPN..<br />

<h2>Environments and Technologies Used</h2>

- A VPN (Proton VPN)
- Microsoft Azure (Virtual Machines/Compute)
-VM located in Central US.
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/adea3aaa-f860-43da-8973-cf93f3e67de1" height="50%" width="50%""/>
</p>
<p>
Create a Resource Group in Azure, then deploy a Windows 10 Virtual Machine within it. Once the VM is set up, use Remote Desktop Protocol (RDP) to log into the VM.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/bff32e42-084f-4d7b-a21d-6fbf57a785cf" height="50%" width="50%"/>
</p>
<p>
Once inside the VM, open a web browser and navigate to https://whatismyipaddress.com/. View the IP information displayed and record it in Notepad or on a piece of paper for later reference.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/efdcd15a-8042-4472-afa1-95a15ed5fcc3" height="50%" width="50%"/>
<img src="https://i.imgur.com/o4XhJYA.png" height="50%" width="50%"/>
</p>
<p>
On your personal computer, sign up for the free version of Proton VPN at https://account.protonvpn.com/signup?plan=free&language=en.
Inside the VM, download and install the Proton VPN client. Log in to the client using your Proton VPN credentials at 
https://account.protonvpn.com/login 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/109506c4-dbc4-49b6-addb-efa0a2ba2f53" height="50%" width="50%"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/a55ab002-0714-483b-91f8-78de87dd9db1" height="50%" width="50%"/>
</p>
<p>
Sign in to the Proton VPN client using the credentials you created during account setup. Once logged in, click "Quick Connect" to automatically connect to a VPN server. Connecting to the VPN will mask your real IP address and encrypt your internet traffic, enhancing privacy and security.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/07c4c427-7ecc-4fe9-bf3a-5eda57b2ec68" height="50%" width="50%"/>
</p>
<p>
Revisit https://whatismyipaddress.com/ and observe the changes in the IP information. Note how the IP now reflects the VPN server you connected to, demonstrating the VPN's effect.
</p>
<br />
