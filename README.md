# consul module 
Consul is a distributed, highly available, datacenter-aware, service discovery and configuration system. It can be used to present services and nodes in a flexible and powerful interface that allows clients to always have an up-to-date view of the infrastructure they are a part of.


use case:
 If 2 people are working on the same infrastructure with terraform using a git repository (e.g. github), but not sharing the terraform.tfstate, terraform might give an error when triying to create or change an infrastructure, becouse terraform doesn't know the remote state of the other person. You will need to share the terraform.tfstate file using consul or S3.
