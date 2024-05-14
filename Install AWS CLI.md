## Configure AWS CLI for Terraform Environment

### Step 1: Create a IAM User with Admin priviledges

* Goto IAM services in AWS Console and click on **Add User**

  ![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/ba3c3638-4e00-4260-aa8e-ec47808fa3e6)

* Provider username and user access to the AWS Management Console as shown below:

  ![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/6fb37f61-ac1e-41c6-8cf4-b787b330ed7a)

* Add **Administrator Permissions** to our user

  ![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/c9f497b8-92e6-4b50-92cc-b29e96433e0b)

* Click on Next and click on **Create User**

  ![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/b813d96c-a500-459b-bb69-8a289b348ecc)

* Once user created, click on the user and select **Security Credentials**  then  click on **Create access key** to generate our key

  ![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/79388359-e379-4802-b2ef-b6e77e387a39)

 Select CLI and click on next

  ![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/8287ca94-a314-4a77-870b-64d23d42616b)

  Click on **Create access key**

  ![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/2a8b4964-2b24-4183-8b79-43a7dfce6a7f)

  Download the access key

  ![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/7007992a-e776-4984-8d19-cf52b307f3fc)


### Step 2: Install the AWS CLI version 2

* To interact with EC2 instances and other AWS resources from the command line, you must install the AWS Command Line Interface (CLI) on your machine. 

* You can download the correct version for your system from this [link](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html). 

* After installing the AWS CLI, you can set it up by running ```aws configure``` command in a terminal window and provide the access key that we generated

  ![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/c0e5f129-2197-426d-a225-3009eef7ee42)

