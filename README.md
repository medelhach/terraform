# terraform Introduction
Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently. 
Terraform can help with multi-cloud by having one workflow for all clouds. The infrastructure Terraform manages can be hosted on public clouds like Amazon Web Services,
Microsoft Azure, and Google Cloud Platform, or on-prem in private clouds such as VMWare vSphere, OpenStack, or CloudStack.
Terraform treats infrastructure as code (IaC) so you never have to worry about you infrastructure drifting away from its desired configuration. 
If you like what you are hearing about Terraform then this repository is for you!

the version we are using : 

Terraform v1.2.3

# Download Terraform

you can count on this link to download Terraform based on your operation systems 
https://www.terraform.io/downloads

# Keypair 

Terraform reads all files with the extension .tf in your current directory 
 1. Create a new directory and go into it 
 2. Create a provider.tf file with the followingcontents;
 ```
 provider "openstack" {}
 
 ```
This specifies the configuration for the OpenStack plugin. You can either specify the configuration in the plugin, or it will automatically load the values from the normal OpenStack environment variable names.
 
 

# Getting started 



the first command to use is initialization steps in order to prepare the current working directory for use with Terraform 
```
terraform init 
```


