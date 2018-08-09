# AWS provisioning with Terraform
## Terraform installation on Ubuntu, I'm using the lastest version 18:04


Download Terraform from their website: https://www.terraform.io/intro/getting-started/install.html, and click on **appropriate package**

```
wget https://releases.hashicorp.com/terraform/0.11.7/terraform_0.11.7_linux_amd64.zip

unzip terraform_0.11.7_linux_amd64.zip -d terraform
```

Add the the location to PATH variable:
```
PATH=$PATH:~/terraform
```


## Setting AWS CLI
Install AWS CLI:
```
apt install python-pip

pip install awscli
```

```
aws configure
```
Add your Access Key ID, ie: DOWPEFJE0F0WIOJ

Add your Secret access key, ie: dqlwefni2489SOJWIOHDS02pdSdjkw8923

Add your region, mine is: eu-west-2

For Default output format [None]: I just hit Return for none



... to be continued
