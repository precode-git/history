# Cupons

Cupons são códigos inseridos pelo cliente ao finalizar um pedido. Ele irá garantir um desconto, que pode ser fixo ou percentual, ao valor total da compra, ao valor do frete ou dos produtos, e segue um conjunto de regras de aplicabilidade configurados pelo seller na criação do mesmo.

## Tabela de Propriedades

| Campo                    | Descrição | Tipo |
| ------------------------ | --------- | ---- |
| utmSource                | UTM source code       | string      |
| utmCampaign?              | UTM campaign code          | string     |
| couponCode               | Coupon code          | string     |
| maxItemsPerClient        | Maximum items per client that the coupon can be applied          | integer     |
| expirationIntervalPerUse |  Coupon expiration interval per use         |  string    |
