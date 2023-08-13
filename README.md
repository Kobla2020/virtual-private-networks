![Screenshot 2023-03-20 174117](https://github.com/Kobla2020/virtual-private-networks/assets/127445078/3e017559-bb5a-459c-88c2-7a5ad9d1c362)

</p>

<h1>Virtual Private Networks (VPN) and how to connect to VPN servers in different countries</h1>
In this tutorial, we set up a virtual private network in a different countries server. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Setting Up VM in Azure
- Checking your IP Address in your VM
- Downloading Proton VPN
- Connecting to a VPN server in another country

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/fc1algy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first thing you want to do is create your VM. Make sure when creating your Vm you choose a region that you are not from. As seen in my other labs, I usually choose U.S. East becuase I am from the east coast but in this lab I chose West Europe.
</p>
<br />

<p>
<img src="https://i.imgur.com/qDyDHwg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now inside of the VM, my Location says that I am in the netherlands which is in west europe. Basically, your VM is like another VPN. (www.whatismyipaddress.com)
</p>
<br />

<p>
<img src="https://i.imgur.com/BCd2NdC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When I go to www.google.com in my VM, it translates everything to the Language people speak in the netherlands. I thought this was fairly interesting.
</p>
<br />

<p>
<img src="https://i.imgur.com/2QHztW2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Search "Proton VPN" on google. When you get to the main page you may have to make an account if you do not have one already ( it may be easier to minimize your VM and make an account in your actual browser). Make sure to get the free version. After your account is made, on the left hand side it will show your dashboard, go down to downloads and when you have the downloads tab open, since we are using the windows operating system, select the windows download version.
</p>
<br />

<p>
<img src="https://i.imgur.com/wPw3GdO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After downloading proton VPN, make sure to finish installing it via the files folder in the "downloads"section. Once you finish the installation, click on the Proton VPN app and enter your credentials you made when initially signing up for Proton VPN. After logging in to the Proton VPN app, on the left side there should be 3 VPN server locations to choose from: United States, Netherlands, and Japan. You can choose which ever server you want from those three options (Since we only have the free version we can only choose from three different locations but if you have the pay as you go version, you should be able to choose any loaction). 
</p>
<br />

<p>
<img src="https://i.imgur.com/a595vBC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now when you choose a server on the Proton VPN app, observe everything that is going on, for example, the traffic, the upload and download speeds, etc. After you are finished, go back to your browser and refresh your "whatismyipaddress.com" page or you can open that page if you dont have it opened already and it should show you a new IP address along with a new location!
