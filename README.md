# Automate building of XSoar and Minemeld
Automate building of XSoar and Minemeld server behind Linux Firewall

This terrarform script builds the following components:
1. VPC (Single)
2. Subnets
  a. Public Subnet (availabilty zone 1)
  b. Private Subnet (availabilty zone 1)
3. SecurityGroups
4. EC2 Instances
5. ENI (public and private) for EC2's

