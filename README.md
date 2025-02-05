![image](https://github.com/user-attachments/assets/8dc47cc4-73d8-45ab-98c6-a6e501fac2f9)

<b>
<h1>Creating and Remotely Connecting to Virtual Machines in Microsoft Azure</h1>
This tutorial will show how to create and remotely connect to virtual machines in Microsoft Azure

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol (RDP 3389)

<h2>Operating Systems Used</h2>

- Windows 10

<h2>Prerequisites</h2>

- Log in and subscribe to Microsoft Azure.
 

<h2>Creating Our First Resource Group</h2> 
  To create our virtual machine, we first need to create a resource group by searching for 'Resource Groups' in Microsoft Azure.
 
  
  Then, click the 'Create' button to set up the resource group.


![image](https://github.com/user-attachments/assets/476fa440-9f36-44ca-bce5-9131b1758378)


<h2>Creating Our First Virtual Machine</h2>
 
 After creating the resource group, we search for "Virtual Machines" in Azure.

 Next, we click the "Create" button to create a new virtual machine.

 Next, we select the resource group we just created to deploy the virtual machine. We choose Windows 10 for the image (optional), set up the username and password, and then create the virtual machine.

<h2>Remotely Connecting to Our Virtual Machine</h2> 

After deploying the virtual machine, we click on it to view its details. Under the "Network" section, we should see the public IP address of our virtual machine. We copy this IP address to our clipboard.

![image](https://github.com/user-attachments/assets/8969efa1-1982-4c01-9f55-91e191c05b67)

Next, we search for 'mstcs' or 'Remote Desktop Connection' on our main Windows PC and open it. (If you're using a Mac, install 'Microsoft Remote Desktop' from the App Store.)

![image](https://github.com/user-attachments/assets/438ee714-2b13-4523-859d-ce9658cf3db9)

Then, we paste (or type) the public IP address of the Windows 10 virtual machine in the provided field.

![image](https://github.com/user-attachments/assets/b2ae8fcc-dd9a-4fb5-8983-7a91637fdb93)

Next, we click on "Show Options" and log in using the username we set when creating the virtual machine.


![image](https://github.com/user-attachments/assets/e0e992fe-c5e9-4ad3-b862-9c2632aaef38)



That's how we create and remotely connect to our virtual machines, hope this helps.
