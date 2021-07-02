# Deploy Logic App standard using ARM

You can refer to the templates available in the repo. You can use deploy custom template option in the Azure Portal or Powershell to deploy the ARM templates.

The template creates the below resources:
1. Creates Storage account which allows traffic from public internet
2. Creates File Share (LogicApp App settings refer to this which create Logic App host runtime directories and files)
3. Creates App Service Plan (Workflow standard -WS1) to host Standard Logic App resources
4. Creates Application Insights for Logic App resource insights
5. Creates the Standard Logic App 


**Disclaimer**: The templates provided are samples, you may verify and make changes as per your requiremenrts. Any concerns or queries feel free to let me know.
