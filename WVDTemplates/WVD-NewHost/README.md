# Windows Virtual Desktop Automated Deployment
This template will
- Allow you to select Windows 10 Client VM for deployment
- Allow you to select Custom Image from Shared Image Gallery
- Auto join your Active Directory Domain
- Download the latest WVD Installer Agent, Bootloader
- Auto configure the new VM(s) to join your Host Pool


----
----

# Requirements:

**Permissions:**
- Azure Active Directory Global Administrator
- Active Directory Administrator
- Account to join AD Domain (optional)

**Infrastructure:**
- Create WVD Tenant
- Create WVD HostPool
- Create Active Directory domain for the new VM(s) to join
- Create a central file share for WVD Profiles
- Generate HostPool Regestration Token

----
----

**New Session Host**

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FDeanCefola%2FAzure-WVD%2Fmaster%2FWVDTemplates%2FWVD-NewHost%2FWVD-NewHost.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FDeanCefola%2FAzure-WVD%2Fmaster%2FWVDTemplates%2FWVD-NewHost%2FWVD-NewHost.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
</a>
