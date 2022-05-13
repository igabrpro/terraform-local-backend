# terraform-local-backend

This repo contains code taht creates null resurce and prints hello world, also included is ```.gitignore``` ignoring ```.terrform/``` and ```terraform.tfstate*```


## Requirements
Install Terraform - [instructions](https://www.terraform.io/downloads)

## Repo content 
```main.tf``` - Terraform configuration file
```.gitignore``` - Terraform file containing the files to be ignored by github

## Guide
1. First download the repo https://github.com/igabrpro/terraform-local-backend.git
2. Change teh directory ```cd  terraform-local-backend```
3. Execute ```terraform init``` in order to download the necessary providers
4. Execute ```terraform apply``` in order to provision the code in main.tf
5. Add the files you want to ignore in the .gitignore
6. Then upload the repo to git
