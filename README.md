# Windows 10 VM with Azure Bastion

Click the button below to deploy a Windows 10 virtual machine with secure Bastion access.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fyourusername%2Fyourrepo%2Fmain%2Fazuredeploy.json)

## Prerequisites

- An active Azure subscription
- Contributor or Owner permissions on the subscription

## What Gets Deployed

- Windows 10 Virtual Machine
- Azure Bastion Host for secure RDP access
- Virtual Network with dedicated subnets
- Network Security Group with RDP rules

## Parameters

| Parameter | Description |
|-----------|-------------|
| adminUsername | Administrator username for the VM |
| adminPassword | Administrator password (must meet complexity requirements) |
| location | Azure region (e.g., eastus) |

## Post-Deployment

1. Navigate to your VM in the Azure portal
2. Click **Connect** → **Bastion**
3. Enter your admin credentials
4. You'll have a secure RDP session in your browser

## Clean Up

Remember to delete the resource group when finished to avoid ongoing costs.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fyourusername%2Fyourrepo%2Fmain%2Fazuredeploy.json)
