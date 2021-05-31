# devops-netology
Project description TBD

# Terraform.gitignore
Due to adding terraform.gitingnore the following files will be egnored:
Local .terraform directories
**/.terraform/*

All .tfstate files:
*.tfstate
*.tfstate.*

Files with crash logs:
crash.log

Files which may collecte sentitive data = it should change depending on environment:
* *.tfvars

All the files collecting overrides and other local changes:
* override.tf
* override.tf.json
* *_override.tf
* *_override.tf.json

CLI configuration files also will be ignored:
* .terraformrc
* terraform.rc

Also .idea/ has been added to the root .gitignore file
