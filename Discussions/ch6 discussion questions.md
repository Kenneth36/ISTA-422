# Chapter 6. Discussion Questions
## Kenneth Clark
### December 12, 2017  


1.	What is a VNET and what is it used for in Azure?

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**Virtual networks (VNets) are used in Azure to provide private connectivity for Azure Virtual Machines (Azure VMs) and some Azure services. VMs and services that are part of the same virtual network can access one another.

2.	The fully managed service in Azure that is used for cross-premises connectivity, is called what?


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**The fully managed service in Azure that is used for cross-premises connectivity is called Virtual Network Gateway.

3.	List three things you need to know when setting up a virtual network.


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**Three things you need to know when setting up a virtual network are address space, subnets, and DNS servers that you want to use.

4.	What is the primary purpose of establishing a subnet?


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**The primary purpose of establishing a subnet is to break up your network into more manageable sections.

5.	When in the deployment process of multiple Virtual Machines(VMs) are the VMs assigned their IP address?


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**The VMs are assigned their IP address as they boot up.

6.	Why should you set the location of the Resource Group?


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**It’s best to specify the same Azure region that will be used for the resources when they are created.


7. What is Role-Based Access Control?


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**  Role-Based Access Control along with the Resource Manager, you can grant permissions at a specified scope: subscription, resource group, or resource. This means you can deploy a set of resources into a resource group and then grant permissions to one or more specific users, groups, or service principal. Those users will only have the permissions granted to those resources in that resource group. This access does not allow them to modify resources in other resource groups. You can also give a user permission to manage a single VM, and that’s all that user will be able to access and administer.


8. Why would you want to create a custom role for role-based access control?


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**  If none of the built-in roles and no combination of the built-in roles provides exactly what you need, you can create a custom role.


9. Consider the Azure portal. What is the dashboard? What is the hub? What is a blade?


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**  The dashboard is the customizable UI that you see when you log into the Azure portal. The hub is the menu on the left of the screen that shows you a core set of options such as Resource Groups, All Resources, and Recent. Blades are the separate sections that get opened as you make selections, when the portal scrolls to the right.


10. Access the conceptual Azure documentation on Github. Search the documentation and answer this question: What happens when I reach the spending limit?


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**  You might have your Azure subscription disabled because you reached your spending limit, have an overdue bill, hit your credit card limit, or because the subscription was canceled by the Account Administrator.