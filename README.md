<h1 align="center">Guardian of Azure: Building Expertise in Sentinel and Detection Strategies</h1>

In this project we'll be focussing on Security Information and Event Management (SIEM) systems. The project comprises of working on and learning Azure Principles for securing Systems in a Network.

![Logo2](https://github.com/kartick1402/Cyber-Security-Project/assets/104575906/4d5c2330-203f-42ae-8460-bcbe1a21dc4d)


## Description

-> **Setting up Azure Resources:** Dive into the Azure portal and create essential resources like a Log Analytics Workspace, Virtual Machines, and Azure Sentinel to lay the foundation for your lab.

-> **Enforcing Network and VM Security Best Practices:** Learn the art of fortifying your network and virtual machines with best practices that keep your environment secure against potential threats.

-> **Data Connectors and Data Analysis:** Harness the power of Data Connectors to funnel data into Azure Sentinel for analysis. Discover how these connectors play a pivotal role in gathering insights from diverse sources.

-> **Windows Security Event Logs:** Delve into Windows Security Event logs, unearthing invaluable insights that can provide a deeper understanding of activities within your environment.

-> **Configuring Windows Security Policies:** Uncover the importance of configuring Windows Security Policies as a proactive measure to maintain a resilient security posture.

-> **Mastering Kusto Query Language (KQL):** Embark on a journey through the realm of Kusto Query Language (KQL), acquiring skills to craft powerful queries that extract meaningful information from logs.

-> **Crafting Custom Analytic Rules:** Elevate your expertise by creating custom analytic rules tailored to detect specific Microsoft Security Events, enhancing your detection capabilities.

-> **Leveraging MITRE ATT&CK Framework:** Explore the renowned MITRE ATT&CK framework, deciphering adversary tactics and techniques. Map these to detection and mitigation procedures for a comprehensive defense strategy.

<h2 align="center">Week-1</h2>

  **The 1st week was all about exploring the Azure Services and getting upto the mark with Basics of Azure, i.e.**
  
  **Azure Fundamentals ->**
  
  **Compute Services ->** The compute services includes topics of Virtual Machines(VMs), Containers and Azure Functions. VMs provide Infrastructure as a Service(IaaS). VM Scale Sets allows multiple configuring of VMs at the same time. Custom Script Extension is an easy to download & run scripts on your VMs, basically used for configuring the system after VM is ready. Containers are basically light weight OS or Environment for a particular app. It is used to launch a particular app directly without waiting for the OS to boot up and then for the app to boot. Azure functions directly uses an app thereby no infrastucture management, thus no need to focus on administrative tasks like installing an OS, instead we can directly deploy our code.
  
  **Network Services ->** The Networking Service of AZURE includes Azure Virtual Network, Azure DNS and Azure Express Route. Azure Virtual Networks allow VMs, Webapps and databases to communicate with each other with users on internet and with our own premises client computer. It supports both PUBLIC and PRIVATE endpoints to enable communication between external or internal resources with other internal resources. Azure DNS is used for hosting DNS domains that provides name resolution using Microsoft Azure. As Azure DNS is based on Azure Resource Manager it provides feature of RBAC to give specific controls to individuals. Azure Express Route helps us to extend our on-premises network on Microsoft Cloud. The connectivity can be any-to-any (IP VPN) network or a point-to-point Ethernet network or a virtual cross-connection.
  
  **Inbound and Oubtound Rule ->** The inbound NAT rule is used to forward the traffic received from a load balancer frontend to one or more instances in the backend pool. The inbound NAT rule is primarily used for port forwarding. Port forwarding allows us to connect to VMs by using the load balancer frontend IP address and port number. Outbound rules allow us to define SNAT(source network address translation) for a public standard load balancer. With outbound rules, we have full declarative control on the connectivity of outbound internet. Outbound rules will only be followed if the backend VM doesn't have an instance-level public IP address (ILPIP).
  
  **IAM and Security Montioring ->** IAM stands for Identity Access Management. It ensures that right person, machines, and software components get access to right resources at the right time. The concept of security monitoring in Azure is performed by services such as Microsoft Defender for Cloud and Microsoft Sentinel. The Microsoft Defender for Cloud and Microsoft Sentinel store their data in a Log Analytics workspace so that one can use log queries to correlate the data collected by the different services. Azure Monitor agent collects the security events and send them to the Event table with other events. For additional features to collect and analyze these events, it is provided by the Microsoft Sentinel.
  
  **RBAC ->** It stands for Role Based Access Control. It helps us to manage the Cloud Resource allocation to diffefent users, how much resources they use, in which area do they have the resource access and what they can do with the resources. The way of using Azure RBAC is to assign Azure Roles. It means how permissions are enforced. The role assignment consists of three elements: security principal, role definition, and scope. The Azure RBAC data is always stored globally and when deleted it's deleted globally. 
  
  **IAM ->** It stands for Identity Access Management. IAM ensures that right person, machines, and software components get access to right resources at the right time. First the client(Person, Machines or Software Components) proves their identity and then they are allowed or refused access to the asked resource. It works with the ideology of Authenticating, Authorizing and Accessing. The most common and well known authenticaton and authorization standards are O Auth 2.0, OpenID Connect(OIDC), JSON Web Tokens(JWTs), Security Assertion Markup Language(SAML), System for Cross Domain Identity Management (SCIM), Web-Services Federation(WS-Fed). 

<p align="center"> <a href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="150" height="150"/> </a> <a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="150" height="150"/> </a> </p>

<h2 align="center">Week-2</h2>

 **The 2nd week was all about Compute Services**
 
Knowing where Data is stored and maintained. This thing is performed in a Data Center which consists of Compute nodes, Switches: connecting the racks, A network topology like hierarchical, Storage (backend) nodes connected to the network, Front-end for submitting jobs and receiving client requests, Software Services. 

![image](https://github.com/kartick1402/Cyber-Security-Project/assets/104575906/a4499ada-8067-43aa-8968-aad246d5c7fb)

System oriented Architecture was also covered in which we came to know what we can do on system specific basis, with the help of cloud we have more flexibililty and even we can build Business Applications which can be used to connect anywhere in the world. Even if we want to build IOT Devices or we want to build some 3D applications or games, we can do this using cloud and further can easily share our resources with anyone over the globe.

![image](https://github.com/kartick1402/Cyber-Security-Project/assets/104575906/e328ca59-906e-4c45-a108-4c4bcf184e27)

The Core Cloud Computing is of 2 types, Based on Deployment Model and Based on Service Model which is distributed in either off-premises or on-premises. The off-premises covers up working in Public and Private Cloud on a Cloud Platform whereas in the on-premises the dedicated hosts run on a local network also called Private Cloud.

![image](https://github.com/kartick1402/Cyber-Security-Project/assets/104575906/03af90b6-b422-4376-83d2-427fb58a25e7)

After this we created a virtual machine in AZURE, following is the video on how to create a Linux Machine in Microsoft Azure Portal.

LINK COMES HERE

To access the machine after creating it in Azure,
1. Type :-  ``` cd downloads ``` 
2. Then, write ``` ssh -i Linux-machine_key.pem azureuser@98.70.33.0 ```
3. Lastly, type ``` sudo su ```
You will be able to access the Virtual Machine as root user.

Following command gives you the server address of any website just replace "portal.azure.com" with desired website URL.

``` nslookup portal.azure.com ```

After creating the VM, we enhanced our understanding on DDoS Attacks, Inbound Oubound Rules and Network Security Group; Installed Apache Server, and learnt about Launching web server at different ports using public IP. 

LINK COMES HERE

<h2 align="center">CONCLUSION</h2>

This is the project solutions architecture as final output:-

![WhatsApp Image 2023-11-03 at 14 38 03_fe355056](https://github.com/kartick1402/Cyber-Security-Project/assets/104575906/6982430c-e9be-4de3-b9c7-4c1150083ffb)

<h1 align="center">Azure Services being used in this Project</h1>

**=> Azure Sentinel => Azure Log Analytics Workspace => Azure Monitor**

**=> Azure Policy => Azure Key Vault => Azure Resource Manager**

**=> Azure Virtual Machines => Azure Network Security Groups**

**=> Azure Data Connectors => Azure Security Center => Azure Active Directory**

