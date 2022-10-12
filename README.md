### Project Title - Deploy a high-availability web app using CloudFormation
This folder has the Udacity Project: Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:


#### network.yml
The CloudFormation code in YAML used in building the cloud infrastructure (network), as required for the project by Udacity

#### network-parameters.json
JSON file of the YAML network.yml .The JSON file contains the parameters. 

### serverss.yml
The CloudFormation code in YAML used in building the cloud infrastructure (servers), as required for the project by Udacity

### server-parameters.json
JSON file of the YAML serverss.yml .The JSON file contains the parameters. 

### create.sh
bash script used to create the infrastructure
run as:  ./create.sh udagram-infra network.yml network-parameters.json;  ./create.sh udagram-servers serverss.yml server-parameters.json for network and servers respectively

### update.sh
bash script used to update the infrastructure after being created
run as:  ./update.sh udagram-infra network.yml network-parameters.json;  ./update.sh udagram-servers serverss.yml server-parameters.json for network and servers respectively

### Udagram Infrastructure Diagram.png
The pictoral description of the infrastructure deployed


### Public URL of the LoadBalancer
 http://udagr-webap-1mrpbhr1c27z3-199120114.us-east-1.elb.amazonaws.com/