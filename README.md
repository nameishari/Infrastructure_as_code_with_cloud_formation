# Infrastructure as code (IAC) with cloud formation

1) Command to create a stack and create resources:
<b> aws cloudformation create-stack  --stack-name myFirstTest --region us-east-1 --template-body file://sample_scripts/create_vpn.yml </b> <- this command will return a stackId if it is successful.
2) In cloud formation, a stack is a group of resources.
