# SKU Service Value
Essa tabela irá conter os valores de serviço vinculado a um SKU Service.
Nela ficarão os dados e configurações específicas para cada valor de serviço.
descrever vinculo com tipo de serviço.

```json
  {
    "Id": 2,
    "SkuServiceTypeId": 2,
    "Name": "Montagem de móveis",
    "Value": 10.5,
    "Cost": 10.5
  }
```
---

| Campo            | Descrição                         | Valor     |
|------------------|-----------------------------------|-----------|
| Id               | Identificador do valor de serviço | numerical |
| SkuServiceTypeId | Identificador do tipo de serviço  | numerical |
| Name             | Nome do serviço                   | string    |
| Value            | Valor do serviço                  | numerical |
| Cost?            | Custo do serviço                  | numerical |
