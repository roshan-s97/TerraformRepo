# TerraformRepo

Repo for consolidating Terraform hcl files across prodapt

## Folder Structure

Please follow below folder structure

|- Cloud Provider
   |- Template Category (Ntier/Kubernetes/etc)
      |- "your component"
         |- your tf folders and files

For example
|- VMWare
   |- Kubernetes
      |- K8sonVmware

## Check and Commit process

Upload your tf codes in dev branch and raise pull request for merging with main branch. 