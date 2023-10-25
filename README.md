The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.

The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on an Azure Sentinel Map!

![3ab09a43-f157-43c9-92bb-504626607728](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/c28294af-ba2d-4841-9c7b-a8c31ee1fa5c)
![Screenshot (120)](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/db6a3a06-f478-4767-8acc-0b370c6ff9e3)
