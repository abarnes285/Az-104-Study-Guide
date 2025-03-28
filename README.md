<h1>Microsoft AZ-104 Study Guide</h1>

<h2>Description</h2>
This document serves as a comprehensive collection of notes and screenshots compiled during my study of the AZ-104 Microsoft Azure Administrator certification guide. Its primary purpose is to reinforce my understanding and retention of key concepts, while also serving as a practical resource for others preparing for the AZ-104 exam. Whether you're reviewing core Azure services, revisiting configuration steps, or looking for real-world visuals, this guide is designed to provide clear, organized, and helpful insights throughout your certification journey.

<h3>Azure manangement options </h3>
You can configure and manage Azure using a broad range of tools and platforms. There are tools available for command line, language-specific software development kits (SDKs), developer tools, migration tools, and many others.   
Tools used for common day-to-day management and interaction include:  <br/>
-Azure portal for interacting with Azure via GUI  <br/>
-Azure PowerShell and Azure CLI for command line and automation-based interactions with Azure <br/>
-Azure Cloud Shell for web-based command line interface <br/>
-Azure mobile app for monitoring and managing your resources from your mobile device <br/>

<h3>Azure Portal </h3>
 The Azure portal is a public website you can access with any web browser. Once you are signed in with your Azure account, you can create, manage, and monitor services and resources. In the portal, you can use search to find different types of services and get links for help on a topic. The Azure portal also guides you through complex admin tasks using wizards and tooltips.  <br/>
-Azure portal is often the best interface for carrying out single tasks, or when you want to look at config options in detail  <br/>
-The portal doesn’t let you automate repetitive tasks. For example, to set up multiple VMs you’d need to create them one at a time. This process might make the portal approach less ideal for repetitive tasks. For these types, we should use Azure PowerShell and CLI.  

<h3>Azure Powershell </h3>
Azure PowerShell lets you connect to your Azure subscription and manage resources.  

For ex. Azure Powershell provides the New-AzVM command that creates a VM inside your Azure subscription. To use it. You launch Powershell and install the Azure Powershell module. Then, sign in to your Azure account using the command Connect-AzAccount and issue a command like:  

>New-AzVM   
 >>-ResourceGroupName “MyResourcesGroup” <br/>
 >>-Name “TestVM” <br/>
 >>-Image “UbuntuLTS”  <br/>
<h3>Azure CLI </h3>
Azure CLI is a command line program that connects to Azure and executes admin commands on Azure resources. Azure CLI can run on windows, Linux, or macOS.  <br/>

-For ex. To create a VM, you would open a command prompt window and install the Azure CLI. Then, sign in to Azure using the command az login and issue a command such as:  <br/>

>Az vm create <br/>
>>--reource-group MyResourceGroup <br/>
>>--name TestVmbr <br/>
>>--image Ubuntu2204 <br/>
>>--generate-ssh-keys <br/>

<h3>Azure Powershell </h3>
Azure cloud shell is an interactive, authenticated, browser-accessible shell for managing Azure resources using scripting tools like Azure CLI or PowerShell. The Cloud shell also has many other dev tools available, such as text editors, source-control tools, databases, and more.  <br/>

-Can access Azure cloud shell from within the portal or by going to this <a href="https://portal.azure.com/#cloudshell/">link</a>.

<h3>Azure Powershell </h3>
The Azure mobile app allows you to access, manage, and monitor all your Azure accounts and resources from your IOS or Android phone or tablet.  
 

Once installed you can perform many common Azure tasks:  <br/>
-Check the current status and critical metrics of your services.  <br/>
-Stay informed with notifications and alerts about health issues.  <br/>
-Review the latest Azure alerts. <br/>
-Start, stop, and restart VMs or web apps. <br/>
-Connect to your VMs.  <br/>
-Manage permissions with RBAC. <br/>
-Use the Azure cloud shell to run saved scripts or perform admin tasks. <br/>

<h3>Azure Powershell </h3>
You can change your default view to the customizable dashboard in the portal settings.  

<h3>Portal menu</h3>
Azure has many more services than whats shown in the menu. The services listed usually are the ones favorited. You can customize your favorites with the specific resource types that you tend to create or administer most often.  

<h3>Copilot in Azure</h3>
If your org has made Copilot in Azure available, you can select the button to ask questions, quickly navigate to services and resources, or get help with tasks. For ex, Copilot can help you design, operate, optimize, and troubleshoot your Azure apps and infrastructure. Copilot for Azure can also help you gain new insights about which Azure services can help with your objectives.  

<h3>Azure portal global controls </h3>
The Azure portal displays several icons in the status bar at the top right side of the screen. These icons are global controls that are always available, no matter what service you’re working with. Each icon provides quick access to useful functionality, such as configuring settings or viewing notifications about portal activity.  

<h3>Cloud shell </h3>
Select the cloud shell icon (>_) to create a new Azure Cloud shell session. Recall that Azure Cloud Shell is an interactive shell for managing Azure resources. This browser-based terminal lets you control and administer your Azure Resources through a command-line interface built right into the portal.  

<h3>Notifications </h3>
Select the bell icon to display the notifications pane. This pane gives you information about the most recent actions that have been carried out, along with their status.  

























































