
1) CloudFormation template that :
* creates two EC2 instances with different operating systems (Amazon Linux 2 and Windows Server 2019)
* a VPC with a single public subnet, an internet gateway, and a security group 
* that allows incoming traffic on ports 22 (SSH) and 80 (HTTP). 
* It also creates a security group and IAM role for the instances,
* configures outgoing and incoming access for ICMP, TCP/22, 80, and 443, and 
* installs NodeJS server on one instance with a "Hello World" web page 
accessible from the internet.
