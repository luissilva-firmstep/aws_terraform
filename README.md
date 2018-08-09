# AWS provisioning with Terraform
## Terraform installation on Ubuntu, I'm using the lastest version 18:04


Download Terraform from their website: https://www.terraform.io/intro/getting-started/install.html, and click on **appropriate package**
Here's the direct link for Linux 64-bit: https://releases.hashicorp.com/terraform/0.11.7/terraform_0.11.7_linux_amd64.zip

Create a folder called Terraform and download terraform  for Linux 64-bit:
```
mkdir ~/terraform

cd ~/terraform
```
```
wget https://releases.hashicorp.com/terraform/0.11.7/terraform_0.11.7_linux_amd64.zip

unzip terraform_0.11.7_linux_amd64.zip -d terraform
```

Add the the location to PATH variable:
```
PATH=$PATH:~/terraform
```

