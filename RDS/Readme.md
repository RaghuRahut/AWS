# Relational Database Service (RDS) 
## Info : Serverless AWS Aurora database is not Public

* Amazon Aurora comes with two Capacity types *Provision* and *serverless*
![alt text](https://github.com/RaghuRahut/AWS/blob/main/RDS/Images/awsauroraCapacityType.PNG?raw=true)
* **Serverless** are not public.Only if **Provision** is choosen, you can configure *public access*
![alt text](https://github.com/RaghuRahut/AWS/blob/main/RDS/Images/awsauroraPublicAccess.PNG?raw=true)


## Info : Roles are auto created based on the capacity types as shown below* 
![alt text](https://github.com/RaghuRahut/AWS/blob/main/RDS/Images/awsaurora.PNG?raw=true)


## Error : Cannot create DB Intance, if VPC doesnot support DNS hostname and resolution.
![alt text](https://github.com/RaghuRahut/AWS/blob/main/RDS/Images/ErrorCreateDatabase.PNG?raw=true)
![alt text](https://github.com/RaghuRahut/AWS/blob/main/RDS/Images/ErrorCreateDatabase1.PNG?raw=true)

## Info : Option Groups and Parameter Groups
* option groups - Additional features of DB Engine
* parameter groups - Manage DB engine configuration

## Info : AWS RDS Proxies Introduction video link 
[AWS RDS Proxy](https://www.youtube.com/watch?v=eMzCI7S1P9M&t=19s)


