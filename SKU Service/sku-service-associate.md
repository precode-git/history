# SKU Service Associate
A associação de serviço vincula um Serviço (SKU Service), composto por um tipo de serviço (SKU Service Type) e valor de serviço (SKU Service Value),
a um Produto (SKU).

## Requisição

### O corpo da requisição deve conter os seguintes campos:
- Identificador do tipo de serviço (`SkuServiceTypeId`)
- Identificador do valor de serviço (`SkuServiceValueId`)
- Identificador do produto (`SkuId`)
- Nome do serviço (`Name`)
- Texto do serviço (`Text`)
- Estado do serviço (`IsActive`)

### Exemplo de estrutura de requisição

```json
  {
    "SkuServiceTypeId": 1,
    "SkuServiceValueId": 1,
    "SkuId": 1,
    "Name": "montagem",
    "Text": "text",
    "IsActive": false
  }
```
---
### Exemplo de estrutura de retorno
```json
  {
      "Id": 1,
      "SkuServiceTypeId": 1,
      "SkuServiceValueId": 1,
      "SkuId": 1,
      "Name": "montagem",
      "Text": "text",
      "IsActive": false
  }
```

| Campo         | Descrição                             | Valor     |
|---------------|---------------------------------------|-----------|
| Id           | Identificador do serviço              | numerical |
| SkuServiceTypeId | Identificador do tipo de serviço      | numerical |
| SkuServiceValueId | Identificador do valor do serviço     | numerical |
| SkuId        | Identificador do produto              | numerical |
| Name         | Nome do serviço                       | string    |
| Text         | Texto do serviço                      | string    |
| IsActive     | Indica se o serviço está ativo ou não | boolean   |

---
