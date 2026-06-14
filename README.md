ARM Template Structure
This deployment uses an ARM template (azuredeploy.json) to provision:
- Virtual Network (burgaVnet)
- Subnet (default)
- Network Interface (burgaNic)
- Virtual Machine (BurgaVM, Ubuntu 18.04)

Parameters are defined in azuredeploy.parameters.json:
- vmName
- adminUsername
- adminPassword
- location

Deployment Validation
The template was deployed successfully in Azure Portal. 
Screenshots include:
- Template deployment success screen
- Resource Group showing BurgaVM
- Nginx running on BurgaVM

