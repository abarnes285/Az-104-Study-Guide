<h1>Microsoft AZ-104 Study Guide</h1>
<h2>Description</h2>
This document serves as a comprehensive collection of notes and screenshots compiled during my study of the AZ-104 Microsoft Azure Administrator certification guide. Its primary purpose is to reinforce my understanding and retention of key concepts, while also serving as a practical resource for others preparing for the AZ-104 exam. Whether you're reviewing core Azure services, revisiting configuration steps, or looking for real-world visuals, this guide is designed to provide clear, organized, and helpful insights throughout your certification journey.
<h3>Azure manangement options </h3>
You can configure and manage Azure using a broad range of tools and platforms. There are tools available for command line, language-specific software development kits (SDKs), developer tools, migration tools, and many others.   
Tools used for common day-to-day management and interaction include:  
-Azure portal for interacting with Azure via GUI  
-Azure PowerShell and Azure CLI for command line and automation-based interactions with Azure 
-Azure Cloud Shell for web-based command line interface 
-azure mobile app for monitoring and managing your resources from your mobile device 
<h3>Azure Portal </h3>
 The azure portal is a public website you can access with any web browser. Once signed in with your azure account you can create, manage, and monitor services and resources. Iin the portal, you can use search to find different types of services and get links for help on a topic. The Azure portal also guides you through complex admin task by using wizards and tooltips.  
-Azure portal is often the best interface for carrying out single tasks, or when you want to look at config options in details  
-The portal doesn’t let you automate repetitive tasks. For example, to set up multiple VM’s you’d need to create them one at a time. This process might make the portal approach less ideal for complex tasks that involve repetition. For these types we should use Azure PowerShell and CLI.  
<h3>Azure Powershell </h3>
Azure powerrshell lets you connect to your azure subscription and manage resources.  

For ex. Azure powershell provides the New-AzVM command that creates a VM for you inside your azure subscription. TO use it. You launch powershell and install the Azure Powershell module. Then, sign in to your Azure account using the command Connect-AzAccount and issue a command like:  
New-AzVM  ‘  
  -ResourceGroupName “MyResourcesGroup” \n
  -Name “TestVM” \n
  -Image “UbuntuLTS” \n
