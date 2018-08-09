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
WS Access Key ID [None]: DOWPEFJE0F0WIOJ

AWS Secret Access Key [None]: dqlwefni2489SOJWIOHDS02pdSdjkw8923

Default region name [None]: eu-west-2

Default output format [None]:
```


... to be continued
