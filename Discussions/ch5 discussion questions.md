# Chapter 5. Discussion Questions
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

7.	What are the four rules to editing a template to redeploy? 


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**
o	If you remove a resource from the template that is not in the resource group, that resource will be unchanged. It won’t be removed simply because it’s gone from the template. (If you want to remove a resource, you have to specifically remove it using the Azure portal, PowerShell, the Azure CLI, etc.).
o	If you add a resource to the template that is not in the resource group, it will create that resource for you when you redeploy the template.
o	Resources that are unchanged but are still in the template will be ignored.
o	Resources that are changed and still in the template will be updated. For example, if we change the address prefixes of our virtual network and redeploy the template, it will change them in the deployed VNet.

8.	Why should you not request a complete deployment using PowerShell?


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**You should not request a complete deployment using PowerShell because you may accidentally remove a section of your template with no way to recover it.

9.	Why did Microsoft create NSGs?


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**Microsoft created NSGs to provide a flexible method for defining the access rules allowing traffic into and out of a VM in a VNet—or even an entire subnet in the VNet.

10.	What is a VPN according to the book?


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Answer:**A VPN Gateway is an Azure managed service that is deployed into a VNet and provides the endpoint for VPN connectivity for point-to-site VPNs, site-to-site VPNs, and ExpressRoute. This gateway is the connection point into Azure from either the on-premises network (site-to-site) or the client machine (point-to-site).


