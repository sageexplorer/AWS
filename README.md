These are the Cloudformation templates, and bash scripts to create a high-availibility network with ELB, Auto-Scaling, Subnets, NAT, and Webservers (apache). VPC.jpeg has the network diagram of this stack. 

Use create.sh to create stack, and update to update. 

network.yml creates network stack. It's parameters are defined in network.json.

demoservers.yml creates servers stack, and it's parameters are defined in demoservers.json


