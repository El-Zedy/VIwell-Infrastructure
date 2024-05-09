# DevOps Assessment Infrastructure :department_store:
VIwell-Infrastructure is a repository containing the infrastructure-as-code (IaC) using `Terraform to` apply assessment infrastructure

This infrastructure have maninly have 5 modules:

1. EKS Cluster itself
2. EKS Nodegroup
3. EKS Addons
4. ECR
5. Network

### To apply it:
    terraform init
    terraform workspace select dev
    terraform apply --var-file dev.tfvars

