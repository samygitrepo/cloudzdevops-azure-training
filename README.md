# cloudzdevops-azure-training
                                    ***Training Materials for Azure Cloud***

**15/Jan/23**

**Demo-1: Installing Azure PowerShell**

https://docs.microsoft.com/en-us/powershell/azure/azurerm/install-azurerm-ps?view=azurermps-6.13.0

**Demo-2: Installing Azure PowerShell**

Install Azure CLI on Windows : https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest
Install Azure CLI on Mac : https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-macos?view=azure-cli-latest  

**Demo-3: Using Azure CloudShell**

**Demo-4: Setting up Budget in Azure Cost Management**

1) Azure Portal --> Cost Management --> Cost Alert --> Create Budget --> Fill in required values
2) Forcasted vs Actual alerts
3) Alert : https://azure.microsoft.com/en-us/blog/prevent-exceeding-azure-budget-with-forecasted-cost-alerts/
4) Action Group : https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/action-groups

**Demo-5: Azure Policy Vs RBAC**

1) Azure Portal --> Search "Policy" and review available policies. Select assignment of polciy "Require a tag on resource groups" --> Assign

https://learn.microsoft.com/en-us/azure/governance/policy/tutorials/create-and-manage

--------------------------------------------------------------------------------------------------------------------------------------------------

**21/Jan/23**

Demo-1: Recource Group Lock

Demo-2: Move Resource Manually

Create 2 RGs --> Create a Public IP in new RG --> Move it other RG --> Notice the Rource ID change

https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/move-resource-group-and-subscription

Demo-3: Move Resources using "Azure Resource Mover" tool from Azure Portal

--------------------------------------------------------------------------------------------------------------------------------------------------

**22/Jan/23**

Demo-1: Creating a simple app service

Demo-2: App service plan demo with vertical and horizontal scaling

--------------------------------------------------------------------------------------------------------------------------------------------------

**28/Jan/23**

Demo-1: App service deployment slots

Demo-2: App service - Web Jobs
https://learn.microsoft.com/en-us/azure/app-service/webjobs-create
CRON Expression example : https://crontab.guru/examples.html

Demo-3: Azure Function

--------------------------------------------------------------------------------------------------------------------------------------------------

**29/Jan/23**

Demo-1: Azure API APPS
https://learn.microsoft.com/en-us/azure/api-management/api-management-key-concepts
https://learn.microsoft.com/en-us/azure/api-management/import-and-publish

Demo-2: Azure CDN
https://learn.microsoft.com/en-us/azure/cdn/cdn-create-new-endpoint

Demo-3: Azure Logic Apps
https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-overview


--------------------------------------------------------------------------------------------------------------------------------------------------

**05/Feb/23**

Netowrking basics : 
Demo-1 : Creating VNET & Subnets

--------------------------------------------------------------------------------------------------------------------------------------------------

**11/Feb/23**

DNS Basics : https://cloudzdevops-my.sharepoint.com/:b:/g/personal/support_cloudzdevops_onmicrosoft_com/ETigJnIZdQVJsAJjU2Smy6kBPPuJzwFccgJzcnYkWYSZVQ?e=W2vfSz

Azure VM Architecture : https://learn.microsoft.com/en-us/azure/virtual-machines/overview

Demo-1 : Azure VM creation - https://cloudzdevops-my.sharepoint.com/:b:/g/personal/support_cloudzdevops_onmicrosoft_com/EcG-gCDHm_BJnJYFU3fgkK0BFk4mh2F1PtCIMnsVzOAKtw?e=Q39SpF

--------------------------------------------------------------------------------------------------------------------------------------------------

**12/Feb/23**

Azure VM Availability Set : 
https://learn.microsoft.com/en-us/azure/virtual-machines/availability-set-overview

Fault Domain & Update Domain : 
https://www.c-sharpcorner.com/article/availability-set-fault-domains-and-update-domains-in-azure-virtual-machie/
https://www.rupeshtiwari.com/azure-update-domain-vs-fault-domain/

Demo-1 : Azure VM Scale set - https://learn.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-create-vmss

--------------------------------------------------------------------------------------------------------------------------------------------------

**18/Feb/23**

Azure Availability Options : https://learn.microsoft.com/en-us/azure/virtual-machines/availability

Demo-1 : Azure Availability Set

Azure Virtual Machine Scale Set (VMSS) vs Availability Set

Availability Zone : https://learn.microsoft.com/en-us/azure/virtual-machines/create-portal-availability-zone?tabs=standard

--------------------------------------------------------------------------------------------------------------------------------------------------

**19/Feb/23**

Azure Bastion : https://learn.microsoft.com/en-us/azure/bastion/bastion-overview

Azure Virtual Desktop (AVD) : https://learn.microsoft.com/en-us/azure/virtual-desktop/overview

--------------------------------------------------------------------------------------------------------------------------------------------------

**25/Feb/23**

Azure Bastion Demo 

Azure Virtual Desktop (AVD) Demo

--------------------------------------------------------------------------------------------------------------------------------------------------

**26/Feb/23**

Azure Automation Account : https://learn.microsoft.com/en-us/azure/automation/overview and it's demo

VNET - VPN & VPN Gateway

VNET - NSG Demo with Linux VM

--------------------------------------------------------------------------------------------------------------------------------------------------

**4/Mar/23**

VNET Peering - Demo

Network Watcher / Network Topology

Network Table / User defined routing (UDR) - Demo

--------------------------------------------------------------------------------------------------------------------------------------------------

**5/Mar/23**

Application Security Group (ASG) - Demo

Azure Load Balancer - Demo

Azure Application Gateway (AAG) - Demo

--------------------------------------------------------------------------------------------------------------------------------------------------

**11/Mar/23**

Azure Front Door (AFD) - Demo

Azure Traffiic Manager (ATM) - Demo

Azure AD Intro - https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-whatis

--------------------------------------------------------------------------------------------------------------------------------------------------

**12/Mar/23**

Azure AD SSPR - Demo
Ref - https://learn.microsoft.com/en-us/azure/active-directory/authentication/concept-sspr-howitworks & https://learn.microsoft.com/en-us/azure/active-directory/authentication/tutorial-enable-sspr

Azure MFA - Demo
Ref - https://learn.microsoft.com/en-us/azure/active-directory/authentication/concept-mfa-howitworks

Azure Conditional Access - Demo
Ref - https://learn.microsoft.com/en-us/azure/active-directory/authentication/concept-mfa-howitworks
