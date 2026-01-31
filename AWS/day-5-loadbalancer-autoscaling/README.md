# AWS Day 5 – Load Balancer & Auto Scaling

## Key Concepts
- Load Balancer distributes traffic across instances
- ALB works at Layer 7 for HTTP/HTTPS
- Auto Scaling adjusts EC2 count based on load

## Production Architecture
- ALB in public subnet
- EC2 instances in private subnets
- NAT Gateway for outbound access

## Interview Notes
- Health checks ensure only healthy instances receive traffic
- Auto Scaling improves availability and cost efficiency

