# Full project environment

The deployment is meant to create a full environment with the following resources:

1. create a new GCP project
2. create a VPC for the client with custom subnet assigned
3. create a VM  and set the network to the custom VPC/subnet
4. create an app engine with different services using the yaml file
5. create storage buckets
6. create cloud Postgres SQL instance
