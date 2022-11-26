# Azure Sentinel Honeypot Lab
Microsoft Azure Sentinel Honey Pot Lab

This is just a quick preview of the Microsoft Azure Sentinel Honeypot lab.  The aim of this lab was to get some experience working with Azure Sentinel and it a fun and worthwhile experience!  My hope is to do a recording of the full lab at some point.

Here are the high level steps excuted during this lab (Method of Procedure).

***WARNING!!! AT TH END OF THE LAB PLEASE REMEMBER TO DELETE ALL THE RESOURCES RELATED TO THIS LAB TO AVOID CHARGES. I REPEAT DELETE ALL RESOURCES RELATED TO THIS LAB!!*****

1. Log in portal.azure.com
2. Start a new subscription called 'Azure subscription 1'
3. Navigate to VIRUTAL MACHINES
4. Create 'Azure Virtual Machine'
5. Under PROJECT DETAILS >> Select Azure subscription 1
6. Under PROJECT DETAILS >> Create a new Resource group 'honeypot1' 
7. Under INSTANCE DETAILS >> virtual machine name 'honeypot1' to match the resource group name.  NOTE: The lab is temporary so I kept everything basic.
8. Under INSTANCE DETAILS >> Region (US) East US to match geographic location
9. Under INSTANCE DETAILS >> Availability options 'No infrastructure redundancy required.' NOTE: It's a test lab so this wasn't necessary
10. Under INSTANCE DETAILS >> Security type 'Standard'
11. Under INSTANCE DETAILS >>Image 'Windows 10 Pro, version 21H2 - Gen2 (free services eligible)
12. Under INSTANCE DETAILS >> VM architecture 'x64.' NOTE: Arm64 is not supported with the selected image.
13. Under ADMINISTRATION ACCOUNT >> Username {MY USER NAME}
14. Under PROJECT DETAILS >> Password {MY PASSWORD}
15. Under PROJECT DETAILS >> Confirm password {MY PASSWORD}
16. Under INBOUND PORT RULES >> Public inbound ports 'Allow selected ports'
17. Under PROJECT DETAILS >> Select inbound ports 'RDP (3389)'
18. Under LICENSING >> Check the box for 'I confirm I have an elegible Windows 10/11 license with multi-tenant hosting rights.'


