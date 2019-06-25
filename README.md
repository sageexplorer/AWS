These are the Cloudformation templates, and bash scripts to create a high-availibility network with ELB, Auto-Scaling, Security Groups, Gateway, Subnets, NAT, and Webservers (apache). VPC.jpeg has the network diagram of this stack. 

Use create.sh to create stack, and update to update. 

network.yml creates network stack. It's parameters are defined in network.json.

demoservers.yml creates servers stack, and it's parameters are defined in demoservers.json

Use create.sh to create Network stack first, and then server stack. Log in to AWS console, and in cloudformation stack, search Outputs for the demo url of the elb. This is the endpoint of the applicaiton once everything is done. 
