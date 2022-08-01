# SKU Service Type
Essa tabela irá conter as especificações do tipo de serviço vinculado a um SKU Service.
Nela ficarão os dados e configurações específicas para cada tipo de serviço.
Descrever que um tipo pode ter muitos valores diferentes.

### Exemplo de estrutura
```json
{
  "Id": 1,
  "Name": "Montagem de móveis",
  "IsActive": true,
  "ShowOnProductFront": true,
  "ShowOnCartFront": true,
  "ShowOnAttachmentFront": true,
  "ShowOnFileUpload": true,
  "IsGiftCard": false,
  "IsRequired": false
}
```
---
| Campo                  | Descrição                                                         | Valor     |
|------------------------|-------------------------------------------------------------------|-----------|
| Id                     | Identificador do tipo de serviço                                  | numerical |
| Name                   | Nome do serviço                                                   | string    |
| IsActive               | Indica se o serviço está ativo ou não                             | boolean   |
| ShowOnProductFront     | Indica se o serviço deve ser exibido na tela de produto           | boolean   |
| ShowOnCartFront        | Indica se o serviço deve ser exibido na tela de carrinho          | boolean   |
| ShowOnAttachmentFront? | Indica se o serviço deve ser exibido na tela de anexo             | boolean   |
| ShowOnFileUpload       | Indica se o serviço deve ser exibido na tela de upload de arquivo | boolean   |
| IsGiftCard             | Indica se o serviço é um cartão de presente                       | boolean   |
| IsRequired             | Indica se o serviço é obrigatório                                 | boolean   |

