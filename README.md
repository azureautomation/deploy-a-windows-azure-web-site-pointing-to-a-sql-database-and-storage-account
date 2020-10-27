Deploy a Windows Azure Web Site Pointing to a SQL Database and Storage Account
==============================================================================

            

[Windows Azure Scripting Center](http://www.windowsazure.com/en-us/documentation/scripts) |
[Get Started with Windows Azure PowerShell](http://go.microsoft.com/fwlink/?linkid=320929&clcid=0x409) |
[Windows Azure Web Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=web&service=all)

Description

Creates a Windows Azure Website and links to a SQL Azure DB and a storage account.


If the storage account specified does not exist, the storage account will be created.


When the SQL Azure database server is created, a firewall rule is added for the client's IP Address and also for Azure Services (to connect to from the new WebSite).


The user is prompted for administrator credentials to be used when creating the login for the new SQL Azure database


**Note:** This script requires an Azure Storage Account to run. The storage account can be specified by setting the subscription configuration. For example,


Set-AzureSubscription -SubscriptionName 'MySubscription' -CurrentStorageAccount 'MyStorageAccount'

Example
 
Scenario
You want to quickly create a new Azure Website and link it to an Azure storage account and a new SQL Azure database.
Requirements

  *  PowerShell Version 3.0 
  *  Windows Azure PowerShell 0.6.18 
See Also

  *  [Set-AzureSubscription](http://msdn.microsoft.com/en-us/library/windowsazure/dn408531.aspx)

  *  [Windows Azure Web Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=web&service=all)

Script Content

The content of the script is reproduced below

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
