# -Google-Cloud-Load-Balancer-Lab

This repository contains the Google Cloud commands and documentation for setting up a basic VM instance with a minimal HTTP Load Balancer.

## Lab Overview
- Create a VPC and subnet
- Configure firewall rules (SSH, RDP, ICMP, and allow internal traffic)
- Create VM instance(s)
- Configure unmanaged instance group
- Setup minimal HTTP Load Balancer
- Test VM connectivity
- Clean up resources after lab                                                                                                                                                     `loadbalancer-lab.sh`: Script with all gcloud commands to recreate the lab
- `screenshots/`: Visual confirmation of VM, load balancer, and firewall rules
- `exports/`: Exported resource lists from gcloud for reference
## Usage
1. Run the script `loadbalancer-lab.sh` to recreate the lab:
```bash
bash loadbalancer-lab.sh
