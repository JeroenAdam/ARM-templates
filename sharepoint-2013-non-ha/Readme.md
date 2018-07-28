<b>This template will create a SharePoint 2013 farm using the PowerShell DSC Extension it creates the following resources:</b>

 A Virtual Network
 Three Storage Accounts
 Two external load balancers
 One VM configured as Domain Controller for a new forest with a single domain
 One VM configured as SQL Server 2014 stand alone
 One VM configured as a one machine SharePoint 2013 farm
 
One external load balancer creates an RDP NAT rule to allow connectivity to the domain controller VM The second external load balancer creates an RDP NAT rule to allow connectivity to the SharePoint VM To access the SQL VM use the domain controller or the SharePoint VMs as jumpboxes

Source:
https://github.com/Azure/AzureStack-QuickStart-Templates/blob/master/sharepoint-2013-non-ha/Readme.md
