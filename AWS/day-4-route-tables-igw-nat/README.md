# AWS Day 4 – Route Tables, IGW & NAT

## Key Components
- Internet Gateway connects VPC to internet
- Route tables define traffic paths
- NAT Gateway allows private subnet outbound access

## Public Subnet
- Route: 0.0.0.0/0 → IGW
- Instance has public IP

## Private Subnet
- No direct IGW route
- Uses NAT Gateway for internet access

## Interview Notes
- Route tables control traffic flow
- NAT Gateway protects private resources

