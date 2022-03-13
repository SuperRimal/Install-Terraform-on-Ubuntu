# Install-Terraform-on-Ubuntu
Step by step walkthrough of Installing Terraform on Ubuntu


## 1. Update the required version

    sudo apt-get update
    sudo apt-get upgrade

   
## 2. Installing Terrafrom using the curl command


    curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
    sudo apt-add-repository "deb [arch=amd64] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
    sudo apt-get update && sudo apt-get install terraform
    
    In case Curl is not installed
    sudo apt install curl
    
## 3. Check Terraform version
      
   
    terrafrom -v or -version
  
