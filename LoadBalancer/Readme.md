# Load Balancer

## Pre-requitises
* OSI Layers and TCP/IP layers
![alt text](https://github.com/RaghuRahut/AWS/blob/main/LoadBalancer/Images/OSI_7layers.PNG?raw=true)
![alt text](https://github.com/RaghuRahut/AWS/blob/main/LoadBalancer/Images/InternetProtocalSuite.PNG?raw=true)

## Collabartion - Launch Template, EC2 Instance, Load Balancer, AutoScaling group etc.
![alt text](https://github.com/RaghuRahut/AWS/blob/main/LoadBalancer/Images/LaunchTemplate.png?raw=true)
##### Notes
* In case, web server needs to be upgraded on production environment, need to upgrade the template as well.
* Template can either be created via Launch template / Launch configuration or via existing EC2 instance.
