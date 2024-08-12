# TerraformASGProject
Terraform project using AWS Auto Scalling Group and ALB load balancer,creating cluster of web servers on Ubuntu with "Hello World".

## 💻 Topics

Integrated with:

- [x] https://aws.amazon.com/
- [x] https://www.terraform.io/
      
## 💻 Pre-requisites

Before you use this project you need to have Terraform installed in your computer and have an account on AWS,and export AWS Access Keys to your terminal.

### Git clone
This will clone the project,install Terraform which is required to run the test.
```
$ git clone https://github.com/Kar1stan/TerraformASGProject.git
$ cd TerraformASGProject
```

## 🚀 Run the project: 
If you want run the project open the terminal and run: 
```
$ export AWS_ACCESS_KEY_ID=45trEayUUu1(example)
$ export AWS_SECRET_ACCESS_KEY=45trEayUUu1(example)
$ terraform init
$ terraform apply
```
If you want to destroy your resources in AWS open the terminal and run: 
```
$ terraform destroy 
```
For further help or additional errors [here]([https://webdriver.io/docs/gettingstarted](https://developer.hashicorp.com/terraform/tutorials/aws-get-started))
