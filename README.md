# Delivering the Modern Data Warehouse with Azure SQL Data Warehouse, Azure Databricks, and Power BI

## Please perform the following manual steps before starting with the lab:

Key Vault-backed secrets and scopes should be enabled
   - Launch Azure Databricks Workspace
   - Go to https://<your_azure_databricks_url>#secrets/createScope (for example, https://westus.azuredatabricks.net#secrets/createScope).
   - Secret scope name: **key-vault-secrets**
   - Managed Principal: Select **Creator**
   - DNS Name: This will be the DNS name assigned to each user-specific Azure Key Vault instance.
     - Can be copied from the Overview blade of the user's Key Vault.
   - Resource ID: This will be the resource ID assigned to the user-specific Azure Key Vault instances.
     - Can be copied from the **Properties** blade of the user's Key Vault.
