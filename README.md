# Data Lake Store - Recursive file operations

These PowerShell sample scripts allow you to recursively perform operations on Data Lake Store files and folders.

## Included scripts

* Get-AdlStoreChildItemRecursive.ps1
* ...

## Prerequisite steps

1. Install [Azure PowerShell on a Windows machine](https://docs.microsoft.com/en-us/powershell/azure/install-azurerm-ps)
2. Open a new PowerShell session.
3. Log in using Login-AzureRmAccount -SubscriptionId <SUBSCRIPTION-ID>

## How to use each script

### Get-AdlStoreChildItemRecursive.ps1

**Syntax**
```powershell
Get-AdlStoreChildItemRecursive.ps1 [-Account] <string> [-Path] <string>
```

**Example**
```powershell
Get-AdlStoreChildItemRecursive.ps1 -Account contosoadla -Path /Samples
```

## Resources

- [Learn more about Azure PowerShell](https://docs.microsoft.com/en-us/powershell/azure/overview)
- [Learn more about Azure Data Lake Store](https://docs.microsoft.com/en-us/azure/data-lake-store/)
