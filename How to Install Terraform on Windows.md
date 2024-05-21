# Installing Terraform on Windows

Installing Terraform on Windows is a straightforward process. Here's a step-by-step guide to help you set it up on your Windows machine:

## Step 1: Download Terraform

* **Go to the [Terraform download page](https://developer.hashicorp.com/terraform/install)**
  
* **Navigate to the Windows section** and download the respective version. Most Windows installations require the amd64 architecture.

![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/5db3f2f4-1fd6-455f-a2a0-540941d81503)

* **Download the Zip File:** Click the download link to get the ZIP file containing the Terraform executable.

## Step 2: Unzip and Move the Terraform Executable

**a. Unzip the Downloaded File:** Extract the contents of the ZIP file. This should give you a single executable file named terraform.exe.

![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/ef7dbd87-f9ce-430d-8e0c-6d0a27a75280)

**b. Move Terraform to a Desired Location:**

   * A common practice is to place terraform.exe in a directory that is part of your system's PATH. This allows you to run Terraform from anywhere in your terminal.
     
   * A good location to move the file to is C:\Program Files\Terraform. If this directory doesn't exist, create it.

## Step 3: Add the Directory to Your System's PATH:

* Open the "Start" menu and search for "Environment Variables."

* Select "Edit the system environment variables."

* In the "System Properties" window, click on the "Environment Variables" button.

  ![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/1bdc1ad4-3bef-4a09-a6cf-7811308f9d08)
   
* Under "System variables," find and select the "Path" variable, then click "Edit."

  ![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/0212135e-a2d8-4e3c-a5ac-be08b9cc90bd)

* Click "New" and add the path where you placed terraform.exe, like C:\Program Files\Terraform.

  ![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/3660219f-a717-407e-be2a-01fdbbc7961c)

  * Click "OK" to close the dialogs and apply the changes.

## Step 4: Verify the Installation

**a. Open a Command Prompt:** Press Win + R, type cmd, and press Enter.

**b. Check Terraform Installation:** 

  - Go to the terraform path C:\Program Files\Terraform 1.8.2
    
  - Type terraform and press Enter.

You should see the Terraform command-line interface output with a list of available commands. If not, double-check that you've correctly set the PATH variable and try again.

![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/1cfa1d03-1fd8-41d7-93cc-7a13b3f56b42)

**c. Verify if the Correct Version of Terraform is Installed**

![image](https://github.com/AnithaPadmanaban04/Getting-Started-with-Terraform/assets/170385807/9b73cdc7-f37b-4742-8358-5da10cac75b6)





