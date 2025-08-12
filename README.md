# Tenable-Scan-and-Fix-a-affected-virtual-machine
Creating a virtual machine in Microsoft Azure and opening the firewall. After the machine is infected, respond and fix the issue 


- Step 1: Creating a new virtual machine in Microsoft Azure

![azureproof](https://github.com/user-attachments/assets/16ac642e-fe50-40df-8720-0732b2f7cd07)




- Step 2:- Login to the VM and prep it for scanning
- Disable Windows Firewall
- Enter into PowerShell to let remote machines configure your VM
- Set-ItemProperty -Path "HKLM:\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System" -Name "LocalAccountTokenFilterPolicy" -Value 1 -Type DWord -Force

-
-
- Sign in to the virtual machine and open the firewall( Allowing the World Wide Web to hack it.)

- Step 3: Scan the breach

- Step 4: Fix the breach ( using Tenable to fix the breach)

- This will involve a vulnerability scan engine

- Will also implement STIGS 
