# Day 2 – Networking Basics & Security Groups

## Goal
Understand basic networking concepts in AWS and practice with EC2 security groups.

## Steps
- Reviewed networking fundamentals: IP addresses, ports, protocols (TCP/UDP).
- Learned how AWS VPC provides isolated networking for EC2 instances.
- Explored default VPC, subnets, and routing tables.
- Created and modified EC2 security groups:
  - Allowed inbound SSH (port 22) from my IP.
  - Allowed HTTP (port 80) for web traffic.
  - Tested blocking/allowing rules by connecting/disconnecting.

## Issues Faced
- Initially couldn’t connect to EC2 until inbound SSH rule was added.
- Realized that “0.0.0.0/0” allows all IPs, which is insecure for production.
- Learned difference between inbound vs outbound rules.

## Lessons Learned
- Security groups act as **virtual firewalls** for EC2.
- Always restrict SSH access to your own IP for security.
- Networking basics (IP, ports, protocols) are essential for troubleshooting.
- AWS networking is flexible but requires careful rule management.

## Reflection
Day 2 taught me how networking works in AWS and how to secure EC2 instances with security groups. This is a core skill for Cloud Support engineers when helping customers with connectivity issues.
screenshot >> https://github.com/saidtay/cloud-support-journey/blob/main/Installed%20Apache.PNG
