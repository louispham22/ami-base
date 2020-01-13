---
title: Description of Base AMI
---
# Description of Base AMI

::: header lang-ja

| Product | HRBC        |
| ------- | ----------- |
| Author  | Kwanhun Seo |
| Status  | Draft 1     |

[[TOC]]

:::

## Description each directory and files

### /cloudinit

- this dir include some of cloud conifg files. that files will work when instances deploy and setting for initial setup.

### /fs

- fs dir include system.d setting files and custom scripts for make and setting file system. 

#### /etc/systemd

- include systemd scripts for enable and setting system.d setting when OS is booted.

#### /usr/libexec

- include some of custom shell scripts. scripts will work for setting hostname and aws env. 

### /script

- include complie, install shell script. when you want to download and complie some project, you can use this script. 

### Jenkinsfile

- Jenkinsfile for Jenkins pipelineJob. 

### ami.env

- Environment information file for AWS. 