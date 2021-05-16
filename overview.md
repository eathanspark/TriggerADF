# Triggering Azure Data factory Pipeline from Console/Windows Application(#)

Azure Data Factory mostally use for ETl activity with has proper schedule to run on the stipuated time in batch mode, but in some of scenarion it is requured on call adf pipeline on demand. Trigger point could any thing like Console Application, windows Services or even web apis. So In this repo I have created a console application that call already create 
ADF pipeline.

# Prerequisite

## Azure Details
- ResourceGroupName = "xxxx";
- FactoryName = "xxxx";
- PipeLineName = "xxxx";
- tenantId = "xxxx";
- clientId = "xxxx";
- clientSecret = "xxxx";
- subscriptionId = "xxxx";
- windowsManagementUri = "https://management.core.windows.net/";
- activeDirectoryEndpoint = "https://login.windows.net/";

## .Net Supporting library 
- Microsoft.Azure.Management.DataFactory;
- Microsoft.Rest;
- Microsoft.IdentityModel.Clients.ActiveDirectory;
- System.Threading.Tasks;
