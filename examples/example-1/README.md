## Deploy Kafka Cluster
This is an example of how to use the terraform_oci_kafka module to deploy a Kafka Cluster in OCI.

**Note**: To keep this example as simple to deploy and test as possible, it deploys the Kafka Cluster into your existing VCN and subnets, all of which are publicly accessible, and  http_port should be configured in security list.  

### Using this example
Update terraform.tfvars with the required information.

### Deploy the cluster  
Initialize Terraform:
```
$ terraform init
```
View what Terraform plans do before actually doing it:
```
$ terraform plan
```
Use Terraform to Provision resources and Kafka Cluster on OCI:
```
$ terraform apply
```
