# API
[Azure Functions を使用して Azure Static Web Apps に API を追加する | Microsoft Docs](https://docs.microsoft.com/ja-jp/azure/static-web-apps/add-api?tabs=vanilla-javascript)

## local.settings.json

```json
{
  "IsEncrypted": false,
  "Values": {
    "AzureWebJobsStorage": "UseDevelopmentStorage=true",
    "FUNCTIONS_WORKER_RUNTIME": "dotnet"
  }
}
```
