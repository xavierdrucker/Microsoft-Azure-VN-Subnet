
<img width="1000" height="250" alt="microsoft-azure" src="https://github.com/user-attachments/assets/86e9ccf8-1383-49a6-a2fe-68b03806d5df" />

# Microsoft Azure VN/Subnet Creation Lab
Creating a Simple Virtual Network in Azure lab.

<h2>Environments and Technologies Used</h2>

- Azure Resource Group
- Azure Virtual Network/Subnet
- Network Security Group

<h2>Operating Systems Used </h2>

- MacBook Air M2 (Host Machine)
- Windows 11 Pro </b> (25H2 ) (Virtual Machine)

<h2> Configuration Steps </h2>

- Step 1 - Create a Resource Group
- Step 2 - Create a Virtual Network on Azure
- Step 3 - Create a Network Security Group
- Step 4 - Associate NSG with Subnet

<h2>Configuration Process</h2>

When signing up for an Azure subscription, create a resource group in the Azure Portal search bar. Once “Resource groups” appears in the search bar, click on it and click Create.
In the screenshot above, the details of the Resource group are as follows:

- Subscription: This refers to the Azure account or billing plan you select to pay for and manage the resources within your Resource Group.

- Resource Group Name: This is the unique name you assign to your Resource Group to identify and organize your resources.

- Region: This indicates the geographic location where Azure hosts your resources. Once filled in, click “Review + Create.”
  
Microsoft Azure resource group has now been created and is ready for use.

<h2> Create an Azure Virtual Network </h2>

<img width="2130" height="753" alt="Screenshot 2026-09-10 at 6 42 27 PM" src="https://github.com/user-attachments/assets/fa7dcd06-fdd0-4244-b811-ac0a63e5a696" />
<p>
<img width="1552" height="1263" alt="Screenshot 2026-09-10 at 6 46 35 PM" src="https://github.com/user-attachments/assets/15d108ae-bb97-446e-b7b5-46d21a3cd54f" />
<p>
Now, let’s begin by searching for “Virtual Networks” in the Azure Portal: Virtual networks → Create. Then choose your Azure subscription, choose a resource group, give the virtual network a name, then choose a region you want the Virtual Network to be in, and then click "Next".
</p>
<img width="1694" height="1258" alt="Screenshot 2026-09-10 at 6 51 08 PM" src="https://github.com/user-attachments/assets/8570b668-1944-4a93-8acc-c2e31da14a08" />
</p>
Now, you will land on this page. Here, you are able to activate Azure Firewall, Virtual network encryption, and whatever security measures you would like to activate, then click Next. 
</p>

<h2> Create a subnet </h2>

<img width="2560" height="1440" alt="Screenshot 2026-09-10 at 6 51 35 PM" src="https://github.com/user-attachments/assets/e0a09e8c-1849-45e0-afd7-895bee5c5608" />

- To rename a virtual network in Azure, click on “Edit virtual network” under “Virtual Network.”

-  Having virtual machines (VMs) on the same virtual network enables them to communicate swiftly and securely with minimal latency, as they reside within the same isolated network environment. This simplifies the setup for tasks such as testing or data sharing between VMs, eliminating the need for intricate routing or public internet access. Next, click on "Review + Create" to be taken to the VM summary page. 
 <img width="749" height="646" alt="Screenshot 2026-09-02 at 10 26 43 PM 2" src="https://github.com/user-attachments/assets/a8e9534d-89b9-4283-83ab-421c352a4045" />
 <img width="1017" height="584" alt="12_create-vm" src="https://github.com/user-attachments/assets/55c606b3-1faa-44d3-b6d7-e590895fe30a" />

- Validation in Azure, during the review and creation of a virtual machine, involves Azure verifying your configuration settings to ensure they comply with requirements such as valid licensing, resource availability, and correct network settings. This step ensures that everything is properly configured before deployment, thereby preventing errors.
<img width="338" height="61" alt="12_create-vm-2" src="https://github.com/user-attachments/assets/d141b517-e834-4227-97af-f224d78c8cb2" />

- Once the validation process is completed, click “Create” to finalize the creation of the virtual machine.
<img width="553" height="460" alt="Screenshot 2026-09-02 at 10 28 20 PM" src="https://github.com/user-attachments/assets/e8b88a7f-e6df-4691-b7f9-0fe5553f0c94" />

- Now your Azure VM should be deploying....–
<h2> Now your Azure VM should be deployed </h2>

<img width="2554" height="1243" alt="Screenshot 2026-09-02 at 11 00 49 PM" src="https://github.com/user-attachments/assets/bf25a326-0f15-44d2-8396-ca80fe8313bc" />

<h2> Use Remote Desktop to test Windows VM </h2>
 <img width="2554" height="1243" alt="Screenshot 2026-09-03 at 5 28 46 PM" src="https://github.com/user-attachments/assets/1a13e090-4adc-4720-8574-399369ec04ad" /> 

 - 💻 RDP from a Mac to a Windows VM
Download the Microsoft Windows App from the Mac App Store.
Open the app and select Add PC.
Enter the VM's Public IP Address.
Enter your Windows VM username and password.
Click Connect to access the VM remotely.

- 🪟 RDP from Windows to a Windows VM
Press Windows Key + R.
Type mstsc and press Enter.
Enter the VM's Public IP Address.
Click Connect.
Enter your Windows VM username and password.
You are now connected to the VM through RDP.

- RDP (Remote Desktop Protocol) lets you control a Windows virtual machine from another computer as if you were sitting directly in front of it.

<img width="2554" height="1243" alt="Screenshot 2026-09-03 at 5 30 51 PM" src="https://github.com/user-attachments/assets/c5bac19c-178f-445d-814e-3600b8fcb754" />

<h2> Conclusion </h2>

- This project showcases the immense power and versatility of Microsoft Azure in creating a virtual machine. It provides hands-on experience with both Windows and Linux environments in a cloud setting. By leveraging Azure’s Resource Groups and virtual networks, users acquire crucial skills in configuring and connecting VMs. This practical experience deepens their understanding of virtualization and network management, laying a solid foundation for mastering virtual machine deployment and virtual network setups in cloud environments.
