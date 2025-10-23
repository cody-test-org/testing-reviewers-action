# Deploy Logic App with Secured storage account having Private Endpoints


At present, we don't have an option to use the Azure portal to deploy Standard Logic App with secured storage account. However, we can work with ARM templates which let us to use the Storage account behind firewall for Logic App standard resource deployment.

 [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fkarpikpl%2FLogicApp-deployment-with-Secure-Storage%2Fmain%2Ftemplates%2FDeployResources.json)

You can refer to the templates available in the templates folder. You can use deploy custom template option in the Azure Portal or Powershell to deploy the ARM templates.

This template has been created from the sample Function App template available here https://github.com/Azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/function-app-storage-private-endpoints

**Disclaimer**: The templates provided are samples, you may verify and make changes as per your requiremenrts. Any concerns or queries feel free to let me know.

## Tech article
https://techcommunity.microsoft.com/t5/integrations-on-azure-blog/deploying-standard-logic-app-to-storage-account-behind-firewall/ba-p/2626286