<p align="center">
<img src="https://i.imgur.com/x499UNB.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Creating a Virtual Machine (Azure)</h1>
This tutorial outlines the creation of a single virtual machine using Microsoft Azure.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machine)



<h2>Operating Systems Used </h2>


- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create an Azure Tenant and Subscription.
- Create a Resource Group in Azure.
- Creat a Virtual Network and a Subnet, while creating your virtual machine.
- Create a Virtual Machine.

<h2>Deployment and Configuration Steps</h2>

1. Create a free Azure subscription. You'll need a credit card for this but dont worry, It's free. Go to google and type in, "free Azure account". Then, choose start with $200 Azure credit and follow the instruction. This should give you $200 in credit for 30 days.
<p>
<img src="https://i.imgur.com/NZ9MpFW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. After you created your free subscription you can look up "Resource Group" in the search bar at the top or click the Resource Group icon. Click create, type the name of the Resource group you desire (I chose "RG-osTicket" for this project), choose your region, click Review + create at the bottom left, once the validation passed you can click create as shown in the pictures below. You now have created a Resource Group.
<p>
<img src="https://i.imgur.com/86YMBxP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/kKkKsGP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/TwUi6Ty.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/ioe9vej.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. In order to create a Virtual Network and a Subnet, you need to create a Virtual Machine first. So, go back to the main Azure page, type in Virtual Machine on the search bar or click on the Virtual Machine icon then, click create and choose Azure Virtual Machine. Select the same Resource Group you just created, name the Virtual Machine you desire (I chose "vm-osticket" for this project), pick the same region from the Resource Group you created and for operating system choose Windows 10 Pro as shown in the pictures below. Then, scroll down for more options.
<p>
<img src="https://i.imgur.com/lNfCRbY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/x8f7MSo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/PjjMpCD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Select the size of your virtual cpu (vcpus, at least 2 vcpus with 16GB memory, in this project I chose 4 vcpus), create a username and a password and make sure to write it down so you won't forget, check the box at the bottom left to confirm then click Next to Disks.
</p>
<img src="https://i.imgur.com/eDujhiB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Keep everything as is for Disks section then, click Next to Networking.
</p>
<img src="https://i.imgur.com/tNgY3ED.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Under Networking, It should have automatically created a Virtual Network, default Subnet and an IP Address, so choose the given options then, click Review + create at the bottom left corner.
</p>
<img src="https://i.imgur.com/ouHFGcj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Once the validation passed, click create to create the Virtual Machine.
</p>
<img src="https://i.imgur.com/Se1u3FU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. Finally, after deployment is complete, click Go To Resource or type in Virtual Machine on the search bar to view the Virtual Machine you just created. CONGRATULATIONS! You now have created your first Virtual Machine in Azure!
</p>
<img src="https://i.imgur.com/WQ9HAkI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<img src="https://i.imgur.com/HiGFXk3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
