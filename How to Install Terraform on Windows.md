# Installing Terraform on Windows

Installing Terraform on Windows is a straightforward process. Here's a step-by-step guide to help you set it up on your Windows machine:

## Step 1: Download Terraform

* **Go to the [Terraform download page](https://developer.hashicorp.com/terraform/install)**
  
* **Navigate to the Windows section** and download the respective version. Most Windows installations require the amd64 architecture.

![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/75dff303-7114-40a1-868d-0902f0ed3a82)

* **Download the Zip File:** Click the download link to get the ZIP file containing the Terraform executable.

## Step 2: Unzip and Move the Terraform Executable

**a. Unzip the Downloaded File:** Extract the contents of the ZIP file. This should give you a single executable file named terraform.exe.

![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/14ea7bc4-89bb-4569-b3bf-305ac0f65862)
   
**b. Move Terraform to a Desired Location:**

   * A common practice is to place terraform.exe in a directory that is part of your system's PATH. This allows you to run Terraform from anywhere in your terminal.
     
   * A good location to move the file to is C:\Program Files\Terraform. If this directory doesn't exist, create it.

## Step 3: Add the Directory to Your System's PATH:

* Open the "Start" menu and search for "Environment Variables."

* Select "Edit the system environment variables."

* In the "System Properties" window, click on the "Environment Variables" button.

  ![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/938398a0-6af4-4208-8cd4-e24d1f9ae52a)

   
* Under "System variables," find and select the "Path" variable, then click "Edit."

  ![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/97425ef9-52d8-476c-9166-de5360e8b91c)

  
* Click "New" and add the path where you placed terraform.exe, like C:\Program Files\Terraform.

  ![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/15373b15-b016-454f-b8da-737f6fc9b33b)

  * Click "OK" to close the dialogs and apply the changes.

## Step 4: Verify the Installation

**a. Open a Command Prompt:** Press Win + R, type cmd, and press Enter.

**b. Check Terraform Installation:** 

  - Go to the terraform path C:\Program Files\Terraform 1.8.2
    
  - Type terraform and press Enter.

You should see the Terraform command-line interface output with a list of available commands. If not, double-check that you've correctly set the PATH variable and try again.

![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/730640d6-6919-48aa-afe8-6a6ccee5e84c)


**c. Verify if the Correct Version of Terraform is Installed**

![image](https://github.com/aniwardhan/Getting-Started-with-Terraform/assets/80623694/811e99f7-e8a6-41f3-9d07-0cccc649e89c)




