# API de Promoções

Promoções são descontos concedidos ao cliente, podendo ser associados a um ou mais produtos do carrinho, ao valor de frete e/ou incluir brindes.  

A API de Promoções deve conter essas três formas diferentes de trabalhar com os descontos, que em todos os casos são aplicáveis na forma de desconto em valor bruto ou percentual:

- #### [[Promoções e Taxas]]
  
  São descontos ou taxas personalizados, podendo ser parametrizados por um conjunto de regras que qualificaram a aplicabilidade da promoção/taxa. Essas regras podem ser definidas por listas de produtos, listas de clientes, quantidade de itens no carrinho, faixas de CEP, dias da semana, entre outros.

- ### [[Cupons]];
  
  São códigos promocionais que aplicam o desconto ao serem inseridos pelo cliente no momento de checkout. A quantidade de usos por cliente e prazo de validade é personalizável.

- ### [[Campanhas de Audiência]].
  
  A ser desenvolvido futuramente.
