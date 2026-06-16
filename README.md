# Windows 10 VM with Azure Bastion

Click the button below to deploy a Windows 10 virtual machine with secure Bastion access.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/[https://raw.githubusercontent.com/jwallaceni/Deploy-Lab/main/azuredeploy.json](https://raw.githubusercontent.com/jwallaceni/Deploy-Lab/refs/heads/main/azuredeploy.json))

## Deployment Parameters

| Parameter | Description |
|-----------|-------------|
| adminUsername | Username for the Windows 10 VM |
| adminPassword | Password for the Windows 10 VM |
| location | Azure region for deployment |

## Post-Deployment

Once deployed, connect to your VM using Azure Bastion from the Azure portal.
