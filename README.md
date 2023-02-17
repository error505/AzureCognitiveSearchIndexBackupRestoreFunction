# AzureCognitiveSearchIndexBackupRestoreFunction
Azure Triggered Function for Azure Cognitive Search Index Backup and Restore

Use this function to make automated backups of Azure Cognitive Search. The backups are stored on the Azure Storage in form on JSON files.
There is another HTTP Function to restore your indexes. You can use it by sending the json body:
{
    "indexName":"filesIndex",
    "date": "1-2-2023"
}


