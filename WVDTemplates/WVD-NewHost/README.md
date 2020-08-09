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
- Active Directory Administrator
- Account to join AD Domain (optional)

**Infrastructure:**
- Create WVD Workspace
- Create WVD HostPool
- Create Active Directory domain for the new VM(s) to join
- Generate HostPool Regestration Token

----
----

**New Session Host**


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fgithub.com%2Fssabih%2FAzure-WVD%2Fblob%2Fmaster%2FWVDTemplates%2FWVD-NewHost%2FWVD-NewHost.json" target="_blank">
  <img src="https://aka.ms/deploytoazurebutton"/>
</a>
