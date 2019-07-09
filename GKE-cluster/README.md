# GKE Cluster

You can create a zonal or regional cluster using the yaml and jinja template. Make sure to
include the schema to ensure that necessary default values are entered if you plan on leaving
some fields empty.

You can also include the k8s-type and the k8s-workload files to create basic deployments with
their corresponding service using deploymnet manage. Note that these deployments are meant to
be basic, there are many deployment options not included here as there are better tools to 
automate k8s resources (such as Helm) or even just saving and deploying YAML templates (see my 
k8s repo for full workloads).
