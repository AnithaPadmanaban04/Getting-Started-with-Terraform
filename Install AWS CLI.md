## Configure AWS CLI for Terraform Environment

### Step 1: Create a IAM User with Admin priviledges

* Goto IAM services in AWS Console and click on **Add User**

  ![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/f0417193-e26f-489b-9be5-f012949334f5)

* Provider username and user access to the AWS Management Console as shown below:

 ![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/ff9a9808-7c3d-4914-8fa5-93f159601bd5)

* Add **Administrator Permissions** to our user

  ![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/ed3e13d6-bd00-49de-ad52-1f769e3e7c1b)

* Click on Next and click on **Create User**

 ![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/a31112d2-0f1f-4571-a49f-13d147c165de)

* Once user created, click on the user and select **Security Credentials**  then  click on **Create access key** to generate our key

 ![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/8e9e1134-2911-44ff-a7fc-74069b91b38d)

 Select CLI and click on next

 ![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/96ec8289-43c0-4898-b3d9-8e56c77fd732)

  Click on **Create access key**

 ![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/f3a0cbbf-0196-445b-ac22-4ff1a60f8f9c)

 Download the access key

 ![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/358fa4e1-cc30-416e-b83d-ced803db8b39)

### Step 2: Install the AWS CLI version 2

* To interact with EC2 instances and other AWS resources from the command line, you must install the AWS Command Line Interface (CLI) on your machine. 

* You can download the correct version for your system from this [link](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html). 

* After installing the AWS CLI, you can set it up by running ```aws configure``` command in a terminal window and provide the access key that we generated

 ![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/c9603021-9cdf-494b-8693-fd94f2f9df98)


