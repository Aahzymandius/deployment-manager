Setting up the Troubleshooting environment

1. Create 2 projects: "shared-vpc" & "gke-ts"

2. Enable the following APIs:
    - compute.googleapis.com
    - container.googleapis.com
    - deploymentmanager.googleapis.com
    - logging.googleapis.com

3. From the Cloud shell of the "shared-vpc" project, run:
gcloud deployment-manager deployments create shared-vpc-resources --config resources.yaml --preview

If all the checks pass, deploy it by running the an update command without specifying the config file:
gcloud deployment-manager deployments update shared-vpc-resources
This will remove the default VPC and will create a new custom VPC which will be used as the shared VPC in the gke-ts project.

