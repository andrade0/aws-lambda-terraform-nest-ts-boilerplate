#Lambda expressJs Boilerplate


####Requirements: 
Terraform needs to be installed in your system ( '$> **which terraform**' should output terraform path )


my versions: 
+ Terraform v0.12.24
+ provider.aws v2.65.0`

run `terraform init` at the root of the project

change package name in nodejs/package.json

edit nodejs/src with the nest app

run `./deploy.sh` to deploy

run `./destroy.sh` to destroy

( make sure to change version in the package.json on every deploy )
