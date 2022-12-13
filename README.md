The Load Balancer's URL: http://udaci-webap-1w8mo89beka4n-988749390.us-east-1.elb.amazonaws.com

To run the Network Infrastructure

> ./create.sh udacity-project-network network/network.yaml network/parameters.json

To run the infrastructure for the application servers

> ./create.sh udacity-project-udagram udagram-app/deploy.yaml udagram-app/parameters.json
