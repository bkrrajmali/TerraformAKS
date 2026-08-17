# TerraformAKS
TerraformAKS
az role assignment create \
  --assignee "<client-id-from-AZURE_CREDENTIALS>" \
  --role "User Access Administrator" \
  --scope "/subscriptions/202d4be6-e0dd-4b9e-84b7-e235d53271a8/resourceGroups/AKS"
