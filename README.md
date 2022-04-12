## Install Azure CLI on your client machine
[Windows](https://aka.ms/installazurecliwindows)
Look for other platforms [here](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli) if you are not on Windows.

## Install Kubernetes CLI
    az aks install-cli
    
## Get AKS cluster credential
    az aks get-credentials --resource-group myResourceGroup --name myAKSCluster

# AKS ARM templates

## Deploy AKS with Kubenet <br/>
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmsftjonw%2FAKS_ARM_templates%2Fmaster%2FAKS_with_Kubenet%2Ftemplate.json)

## Deploy AKS with Azure CNI <br/>

Create an Azure virtual network <br/>
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmsftjonw%2FAKS_ARM_templates%2Fmaster%2FAKS_with_AzureCNI%2Fazure_vnet_template.json)

Create AKS with the created virtual network <br/>
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmsftjonw%2FAKS_ARM_templates%2Fmaster%2FAKS_with_AzureCNI%2Faks_template.json)




