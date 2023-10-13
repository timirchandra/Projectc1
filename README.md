# Project1
Azure network
Create two separate networks, Site1 and Site2.
Site1 has the IP address 172.20.0.0/16, and within its virtual network, there are three subnets: I. Appserver (172.20.10.0/24) II. Work Subnet (172.20.20.0/24) III. DB subnet (172.20.30.0/24). 
Site2, on the other hand, has the IP address 172.16.0.0/16, and its virtual network contains four subnets: I. Account (172.16.10.0/24) II. HR (172.16.20.0/24) III. Development (172.16.30.0/24) IV. Administration (172.16.40.0/24). 
Establish a peering connection for communication between these two distinct networks (Site1 and Site2). 
Next, we need to launch VM2 with both a public and private IP address under the Administration subnet in Site2's virtual network. 
Similarly, launch VM1 with a private IP address under the Work Subnet subnet in Site1's virtual network. Additionally, attach network storage to VM1.
Moving on, launch VM3 with both a public and private IP address under the DB subnet in Site1's virtual network and attach a Database server to it.
Lastly, launch VM4 and VM5 in the Appserver subnet and establish connectivity via a LoadBalancer.
