# Amazon VPC Peering 

Amazon VPC is a service that helps you launch AWS resources in a logically isolated virtual network you define. You have complete control over your virtual networking environment.

![Isolated VPCs](https://github.com/Benn1440/VPC_Peering/assets/67696393/0494d760-2ac4-4a37-904b-9aa7f8c5dba2)


Basically, VPCs are usually isolated from each other. A VPC Peering connection is a networking connection between two VPCs that you can use to route traffic between them by using private IP addresses.

![VPC Peering Tab](https://github.com/Benn1440/VPC_Peering/assets/67696393/ecf78c75-79bf-4d69-bf88-486e1b03bd51)

A critical property of a subnet is its route table. Which usually contains a set of rules, called Routes, Routes determine where network traffic, from your subnet or gateway is directed. 

After selecting the Peering Connections, Your VPC will request that another VPC allow access to its resources. The VPC that makes the request is called the Requester. You can request access to VPCs from other AWS Accounts.

![VPC Adapter](https://github.com/Benn1440/VPC_Peering/assets/67696393/c5f49044-6352-4a9b-8e7e-8e48afce76dd)

When a VPC peering is created, you have to accept it to activate, if the peering connection is across accounts both accounts must accept the connections to activate it.

![Tryto connect to M and F](https://github.com/Benn1440/VPC_Peering/assets/67696393/71eb00d6-2c09-410a-ab57-1b4acf74e95c)

After a connection is established you must modify the route table associated with each VPC. You must add a route into each route table to allow traffic to be routed to the peered VPC.

![Successful VPC Peering](https://github.com/Benn1440/VPC_Peering/assets/67696393/a76d05c1-4aca-4598-a472-465a95609729)

Even after creating a VPC connection, peered VPCs do not necessarily accept all data between them.
Security features like network access control lists and security groups still apply, and you need to update them.
You need to configure the CIDR and specify.

![Success ping btw Instances](https://github.com/Benn1440/VPC_Peering/assets/67696393/63ca31ed-fc0a-46ff-89a4-d4834aed0d41)


