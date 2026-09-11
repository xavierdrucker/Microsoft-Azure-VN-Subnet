<img width="1365" height="768" alt="Gemini_Generated_Image_9r4hdc9r4hdc9r4h" src="https://github.com/user-attachments/assets/ecca4702-ae99-4bc0-961a-a5dc34ca35a4" />


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

Now, let’s begin by searching for “Virtual Networks” in the Azure Portal: Virtual networks → Create. Then choose your Azure subscription, choose a resource group, give the virtual network a name, then choose a region you want the Virtual Network to be in, and then click "Next".

<img width="2130" height="753" alt="Screenshot 2026-09-10 at 6 42 27 PM" src="https://github.com/user-attachments/assets/fa7dcd06-fdd0-4244-b811-ac0a63e5a696" />
<img width="523" height="299" alt="Screenshot 2026-09-10 at 6 43 41 PM" src="https://github.com/user-attachments/assets/87f7cc2a-658e-413c-9a68-1bd51ef5c61a" />
<p>
<img width="1552" height="1263" alt="Screenshot 2026-09-10 at 6 46 35 PM" src="https://github.com/user-attachments/assets/15d108ae-bb97-446e-b7b5-46d21a3cd54f" />
<p>
</p>
<img width="1694" height="1258" alt="Screenshot 2026-09-10 at 6 51 08 PM" src="https://github.com/user-attachments/assets/8570b668-1944-4a93-8acc-c2e31da14a08" />
</p>
Now, you will land on this page. Here, you are able to activate Azure Firewall, Virtual network encryption, and whatever security measures you would like to activate, then click Next. 
</p>

<h2> Create a subnet </h2>

<img width="1586" height="1265" alt="Screenshot 2026-09-10 at 6 51 35 PM" src="https://github.com/user-attachments/assets/117660ae-214c-4da3-885e-869e36fa427f" />

- Now, on this page you'll be able to create a subnet. After you create one, click Review + Create

<img width="1592" height="1232" alt="Screenshot 2026-09-03 at 5 06 37 PM" src="https://github.com/user-attachments/assets/e5c710d0-0ee9-4220-8f2b-9a58641f49ac" />

<img width="338" height="61" alt="12_create-vm-2" src="https://github.com/user-attachments/assets/d141b517-e834-4227-97af-f224d78c8cb2" />

- If everything looks good, then click Create, and the virtual network will be deployed.






  
<h2> Conclusion </h2>
