# Creating-a-Virtual-Machine-in-Azure
<p align="center">
</p>

<h1>Virtual Machine- Creating-a-Virtual-Machine-in-Azure
</h1>
This tutorial outlines the process for creating a new Virtual Machine in Azure.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 11</b> (21H2)

<h2>List of Prerequisites</h2>

- Windows VM
- IIS
- SQL database
- Required PHP Extensions

<h2>Creating VM for osTicket download</h2>
First step is to create a resource group in Azure. To do this we open azure and go to the resource groups tab, and then select the +Create button. Name your group however you would like and select a region that works best for you. (I typically use East US 2). Once that is complete, select Review + Create.<p>

Once you have your resource group created you can start the process for creating a VM.</p>
- First go to the VM tab in Azure, then select create.</p>
</p>
- Make sure you have the correct subscription selected, and then select the resource group that was just created.</p>
</p>
- Name your VM however you would like.</p>
</p>
- Select the same Region as you did for your resource group.</p>
</p>
- Next is to select the image, this is going to be the operating system for your VM (there are many options from Linus, windows, Mac, and more)</p>
</p>
- then select an appropriate size for what you are going to be working on.</p>
</p>
- Create the username and password for the VM.</p>
</p>
- After that you can cycle through the following screens by pressing next (if you need any special setting or security this is where it can be setup).</p>
</p>
- Finally select Review + Create.</p>

Congratulations you have created a Azure VM!</p>
</p>
To access your new VM you will go to your VM tab in Azure, click on the VM you created and locate the Public IP address from the Networking section.</p>
Now open Remote desktop on your computer and enter the Public IP address and the username and password created for your VM.</p>
This should then start and open your new VM on your computer.</p>
