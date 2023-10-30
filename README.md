<h1 align="center">Guardian of Azure: Building Expertise in Sentinel and Detection Strategies</h1>

In this project we'll be focussing on Security Information and Event Management (SIEM) systems. The project comprises of working on and learning Azure Principles for securing Systems in a Network.

![Azure Sentinelnew](https://github.com/kartick1402/Cyber-Security-Project/assets/104575906/0ddc35dd-75fe-42bc-bade-a3eabfe93f62)

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

 **The 2nd week was all about .....**

<h1 align="center">Azure Services being used in this Project</h1>

**=> Azure Sentinel => Azure Log Analytics Workspace => Azure Monitor**

**=> Azure Policy => Azure Key Vault => Azure Resource Manager**

**=> Azure Virtual Machines => Azure Network Security Groups**

**=> Azure Data Connectors => Azure Security Center => Azure Active Directory**

