# Packer
Packer Demo Repo

https://learn.hashicorp.com/tutorials/packer/get-started-install-cli?in=packer/aws-get-started


## Install

```bash
wget https://releases.hashicorp.com/packer/1.8.2/packer_1.8.2_linux_amd64.zip
unzip packer*.zip
mv packer /usr/local/bin
```

## Packer Commands

You must have AWS access configured on your shell.

```bash
packer init .
packer fmt . #format mile
packer validate .
packer build .
```
