# Exemplo de serviço de garantia extendida:

## SKU Service Type
```json
  {
    "Id": 2,
    "Name": "Garantia Extendida",
    "IsActive": true,
    "ShowOnProductFront": true,
    "ShowOnCartFront": true,
    "ShowOnAttachmentFront": true,
    "ShowOnFileUpload": true,
    "IsGiftCard": false,
    "IsRequired": false
  }
```

## SKU Service Values
```json
  {
    "Id": 2,
    "SkuServiceTypeId": 2,
    "Name": "Garantia Extendida Celular - 12 meses",
    "Value": 100,
    "Cost": 70
  }
```
```json
  {
    "Id": 3,
    "SkuServiceTypeId": 2,
    "Name": "Garantia Extendida Celular - 24 meses",
    "Value": 170,
    "Cost": 80
  }
```

## SKU Service Associate
```json
  {
    "SkuServiceTypeId": 2,
    "SkuServiceValueId": 2,
    "SkuId": 1,
    "Name": "Garantia Extendida Celular - 12 meses",
    "Text": "Garantia Extendida - 12 meses",
    "IsActive": true
  }
```
```json
  {
    "SkuServiceTypeId": 2,
    "SkuServiceValueId": 3,
    "SkuId": 1,
    "Name": "Garantia Extendida Celular - 24 meses",
    "Text": "Garantia Extendida - 24 meses",
    "IsActive": true
  }
```

