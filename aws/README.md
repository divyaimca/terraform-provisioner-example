# terraform-provisioner-example

## 1st generate the aws_access_key and aws_secret_key  in terraform.tfvars file
## 2nd create the key private-public pair 
  generate a key pair in your local system (ssh-keygen -f KumaprdKeys -t rsa)
  under security and network -> key pair -> upload public key 

This example will create an instance in aws, create a sg with port 22 and 80 on, install nginx with remote-exec provisioner, copy a script from local to remote with file provisioner and using local exec it will copy a file back to local system.
