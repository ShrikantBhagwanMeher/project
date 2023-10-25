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

CREATING A CUSTOM LOG 
![3](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/8c12b084-504e-41c6-a2ff-834d71c2d9f9)

GIVING THE PATH OF FAILED RDP FILE IN THE CUSTOME LOG
![4](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/bdfd196c-510f-457e-a706-e069b4f5f83e)

GIVEN THE CUSTOM LOG A NAME
![5](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/502dba2f-8b51-4a4c-ac41-a60fa6f36966)

It will show the log file named FAILED RDP WITH GEO CL (CL stands for custom logs)
![6](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/b5bef4be-4179-4cef-ba0f-e4556600e6ff)

COPY THE FILE AS USE IT AS A QUERY IN BARD AS IT WONT RUN AZURE DUE TO RESTRICTION ON STUDENT SUBSCRUBTION
![1](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/3b402398-32e8-47c4-b06f-6dbfefe79951)

Bard will take the file name as a query and show the live location of the attackers.
![6](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/efbd574a-ea5b-4f93-80b8-ac75473b8973)
![5](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/6a771287-3eb5-4b13-8623-c7176282c5ac)
![4](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/a4869a74-d58a-4f35-8527-85081e17731e)
![3](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/7f497cd2-03d6-4e93-9dd6-599ef98aa6b5)
![2](https://github.com/ShrikantBhagwanMeher/project/assets/145743330/a9b6f08d-3fd9-4082-a7cb-846d5917723e)


