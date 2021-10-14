## Project 3

### Part 1

* VPC
```
VPC can provide a private cloud that contains a certain range of IP adresses from users chose subnets.
```
* Subnet
```
Subnet is a range of IP adresses that we choose
```
* Internet gateway
```
Internet gateway can allow us to connect to the internet
```
* Route table
```
Route table is to define the traffic communication rules
```
* Security group
```
Security group is the firewall for my VPC that only certain port can access it.
```

### Part 2

* 1.Instance details
```
AMI tpye: Ubuntu Server 20.04 LTS (HVM), SSD Volume Type
Instance type: t2.micro
```
* 2.How to attach instance to VPC
```
At Configure Instance details, select VPC that want to connect to for Network
```
* 3.Public IP address auto-assign -yay or nay and why?
```
It's not auto-assigned, I only have a private ip address. Because I have to rent an elastic ip address or someone pay for an IP address that I can connect to the instance
```
* 4.How to create and attach storage volume to instance
```
At add storage, select defult or click Add New Volume
```
* 5.How to tag instance with "Name" of "YOURLASTNAME-instance"
```
At add tags, click Add Tag, put Name in Key and put YOURLASTNAME-instance in Value
```
* 6.How to associate VPC security group (your security group) with your instance
```
At configure security group select Select an existing security group, and select the sg that you created
```
* 7.How to create/reserve and associate and Elastic IP address with your instance
```
At Elastic IPs, click allocate Elastic IP address, then add a new tag.
After allocate, use actions to associate Elastic IP address to the instance that you want.
```
* 9.How to change hostname via commands on instance
```
sudo hostname Liu-ubuntu
```
