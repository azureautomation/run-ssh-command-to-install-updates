Run SSH Command to Install Updates
==================================

            

This runbook provides an example of how to run a command on a Linux machine from Azure Automation.   The command parameter defaults to 'sudo apt-get update ; sudo apt-get upgrade' to retrieve and install of the available updates on the machine.
    


REQUIRED AUTOMATION ASSETS  
1. SSH PowerShell module:      http://www.powershellgallery.com/packages/SSH/1.0.0 or search 'SSH' by JoeLevy on the Automation Module Gallery  


2. An Automation connection asset containing the connection information needed to remote to your Linux machine

 

 


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
