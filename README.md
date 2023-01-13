# AzureDeploymentRepo with bicep
Repo to work with Github Actions to Deploy Bicep into Azure - Learning

## 1. Preparation
  - Learn Bicep
  - Learn Git & GitHub
  - Learn GitActions
  - Azure is ez no need to learn

## 2. Prepare Bicep file
  - prepare bicep file
  - add add parameters.json
  - add some modules

## 3. Azure Preparation and set scope
  - Make Service Principal ``` az ad sp create-for-rbac --name {PrincipalName} --role contributor --scopes /subscriptions/{subscription-id}/resourceGroups/exampleRG --sdk-auth ```
  - copy output
## 4. Make GitHub secret
  - AZURE_SP_CREDENTIALS = output
  - AZURE_SUBSCRIPTION = sub id
  - any needed secret (like Resource Group)

## 5. Create Workflow
  - to much to be here
