Create the VPC using ansible. Make sure the code work in every region of AWS.  
==============================================================================
<img width="800" alt="Screenshot_507" src="https://user-images.githubusercontent.com/13994900/80219066-a5a26d80-8607-11ea-84ff-eeffbadce3da.png">





Requirements
------------
In order to work with Python 2.7.16, install next packages:
* yum install ansible -y
* amazon-linux-extras install ansible2
* yum install python-boto3 -y
* yum install python-pip -y
*  pip install boto awscli





Issues 
=======
1)  This  issue you will get when the List of Elasti IPs will be 5. In order to solve the problem, delete one EIPs and run again.

<img width="954" alt="Screenshot_492" src="https://user-images.githubusercontent.com/13994900/80157006-e1e3b880-858a-11ea-8833-1b62cdc3e130.png">

2) To solve the next issue, use #map_public: yes , under each Public Subnet!
<img width="924" alt="Screenshot_491" src="https://user-images.githubusercontent.com/13994900/80157055-ffb11d80-858a-11ea-9e28-276768fd89b8.png">

<img width="244" alt="Screenshot_494" src="https://user-images.githubusercontent.com/13994900/80157606-2b80d300-858c-11ea-8a87-4f1b0ee8a178.png">
                              
 
Time spent on  project
===========================

<img width="350" alt="Screenshot_500" src="https://user-images.githubusercontent.com/13994900/80165896-2cbcfa80-85a2-11ea-84f7-408e7d78a54a.png">

<img width="350" alt="Screenshot_508" src="https://user-images.githubusercontent.com/13994900/80219237-cec2fe00-8607-11ea-808c-8afb24351b88.png">
