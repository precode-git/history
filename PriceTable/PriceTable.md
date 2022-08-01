## Criação da tabela de preços, baseada no seguinte modelo de resposta:
```json
{
    "itemId": "1",
    "listPrice": 50,
    "costPrice": 90,
    "markup": 30,
    "basePrice": 117,
    "fixedPrices": [
        {
            "tradePolicyId": "1",
            "value": 50.5,
            "listPrice": 50.5,
            "minQuantity": 2,
            "dateRange": {
                "from": "2021-12-31T01:00:00Z",
                "to": "2022-12-31T01:00:00Z"
            }
        },
        {
            "tradePolicyId": "2",
            "value": 30,
            "listPrice": 50,
            "minQuantity": 2
        }
    ]
}
```
| Campo       | Descrição                                                               | Valor        |
|-------------|-------------------------------------------------------------------------|--------------|
| itemId      | sku do item para o qual o preço será aplicado                           | numerical    |
| listPrice   | preço sugerido para o sku na lista                                      | float        |
| costPrice   | preço de custo para o sku                                               | float        |
| markup      | margem de lucro desejada para o sku                                     | float        |
| basePrice   | preço de referência do sku                                              | float        |
| fixedPrices | regra de preço que substitui todas as configurações da tabela de preços | array (null) |

| Campo         | Descrição                                                                 | Valor            |
|---------------|---------------------------------------------------------------------------|------------------|
| tradePolicyId | id da regra de preço fixo                                                 | numerical        |
| value         | valor fixo para a regra                                                   | float            |
| listPrice     | preço de lista para a regra                                               | float            |
| dateRange     | define data de inicio (from) e fim (to) para a regra                      | date-time (null) |

## Definição
Estrutura de precificação para os produtos disponibilizados no e-commerce, configuráveis pelo seller, com a opção de 
serem adicionadas regras específicas para alteração dos preços. Os registros dessa tabela serão vínculados por sku 
individual, proporcionando maior dinamicidade dos preços.

