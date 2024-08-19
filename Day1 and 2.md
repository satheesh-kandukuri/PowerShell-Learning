Powershell History:
GUI --> CLI
Perform same actions we do in GUI should do using CLI, CLI uses less resources.
using CLI we can do Automation
ex: I have 500 servers, want to get Database patch infomation --> manually doing this activity is impossible, so these kind of situations we can use Automations.

PowerShell is a cross-platform task automation solution made up of a command-line shell, a scripting language, and a configuration management(DSC desired state configuration) framework. 
It works with Commands only.

Powershell CLI shell builts on .NET Framework means that powershell commands uses .NET classes and Methods to interact with system.

.NET Framework is a software development framework used to develop software applications.It is designed and developed by Microsoft.

ex: Get-Service
if you run this cmd it will return out put like below, but internally it will access the .NET classes
![image](https://github.com/user-attachments/assets/be7fdcaf-d0f6-4817-b5b8-51b1c7476443)

PS C:\Users\k> Get-Service

Status   Name               DisplayName
------   ----               -----------
Stopped  AarSvc_4b114c      Agent Activation Runtime_4b114c
Running  AdobeARMservice    Adobe Acrobat Update Service
Running  AESMService        Intel® SGX AESM
Stopped  AJRouter           AllJoyn Router Service
Stopped  ALG                Application Layer Gateway Service
Stopped  AppIDSvc           Application Identity
Running  Appinfo            Application Information

