The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.

The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on an Azure Sentinel Map!

![3ab09a43-f157-43c9-92bb-504626607728](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/c28294af-ba2d-4841-9c7b-a8c31ee1fa5c)
![Screenshot (120)](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/db6a3a06-f478-4767-8acc-0b370c6ff9e3)

Entering the geo pin
![4c54f854-7d9c-4776-8bd8-60a650427ce2](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/217e63a8-3a99-4012-8f4a-132b0d3d214a)

DEMO ATTACK ON THE VIRTUAL MACHINE!
[e6fdb357-f0c1-4816-bd17-0a715b25fdd1](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/5ecb0893-3a0e-454b-a510-8d0965a2ce99)

NEW ENTRY IN THE POWERSHELL WITH THE LIVE LOCATION AND THE TIME OF ATTACKING
![6bcb97ef-f042-4d9b-bdc9-e8ec9802c377](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/254066d3-5069-4ee4-a7ef-626723f332a6)
