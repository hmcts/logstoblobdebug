# logstoblobdebug-arm-bug-reproducer

Update these values in parameters.json

```
"env": {
    "value": "environment name"
    },
"asp_name": {
    "value": "asp name"
    },
"asp_rg": {
    "value": "asp resource group"
    },
```

```
az group deployment create --name logstoblob-debug -g logstoblob-debug --template-file logstoblob.json --parameters parameters.json
```
