# Devopsweek5

Steps to Complete the Assignment
1. Setting Up a Domain

Create an Azure Account:

I started by creating an Azure account and logging into the Azure portal.

Register a Domain:

I registered a domain through a domain registrar service (e.g., GoDaddy).

2. Setting Up a Server on a VM

Create a Virtual Machine (VM):

I navigated to the Azure portal and created a new Virtual Machine.
I selected the desired operating system (e.g., Ubuntu) and configured the necessary settings like size, resource group, and network.

Configure the VM:

Once the VM was created, I connected to it via SSH using the provided public IP address.
I installed necessary software and configured the server environment according to my requirements.
3. Using the DNS Server for Traffic Management

Configure DNS Settings:

I accessed the DNS settings in my domain registrar account.
I updated the DNS records to point to the public IP address of my Azure VM.

Test DNS Configuration:

I used tools like nslookup and ping to verify that the domain name was correctly resolving to the VM’s IP address.
4. Creating and Testing Azure Application Gateway

Create an Application Gateway:

I followed the steps in the Azure portal to create a new Application Gateway.
I configured the frontend IP, backend pool, and routing rules.

Configure Backend Pool:

I added my VM to the backend pool of the Application Gateway.
Set Up Health Probes and Listeners:

I configured health probes to monitor the status of my VM.
I set up listeners to handle incoming traffic on the specified ports.

Test the Application Gateway:

I accessed the public IP of the Application Gateway to verify that it correctly routed traffic to my VM.
I performed various tests to ensure that the Application Gateway was working as expected.
