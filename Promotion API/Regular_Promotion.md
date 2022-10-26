# Promoção Regular

Promoção de uso padrão, sem um conjudo pré-definido de regras, que pode ser configurada pelo seller no momento da criação. 

## Campos Obrigatórios

Os campos obrigatórios para esse tipo de promoção são os seguintes:

- **Nome**: *Nome da Promoção*

- **Status**: *Ativa ou desativa a Promoção*

- **Descrição**: *Descrição interna da Promoção. Usado na comunicação interna da loja para identificar a origem da promoção*

- **Prazo de Validade**: *Configura o início e fim da Promoção, podendo ser definidos prazos futuros para lançar a promoção no website, se configurada dessa forma o status será marcada como inativo até o prazo inicial da Promoção*

- **Tipo de desconto**: *Define o tipo de desconto que será aplicado, podendo ser Nominal, Nominal no Frete, Percentual, Percentual no Frete, Preço Máximo por Item, Frete Máximo, Brinde, Desconto Nominal Baseado em Fórmula, Nominal por valor de Recompensa, Percentual por Valor de Recompensa, Tabela de Valores Promocionais*

## Em quais itens a promoção será aplicada?

Caso não queira aplicar a todos os produtos, o seller poderá definir por critério de inclusão ou exclusão os itens aos quais será aplicado a promoção. Deve ser disponibilizadas opções de aplicar promoção por:
- **Categoria**, 
- **Marca**, 
- **Coleção**,
- **Produto**,
- **SKU**.

## Definindo as Regras de Aplicabilidade

O seller poderá escolher dentro do conjunto de critérios as condições que os clientes deverão atender para terem direito aos benefícios da promoção, que serão:

- **Valor mínimo ou máximo do pedido**: *Considera o valor do carrinho, sem considerar descontos ou valor de frete*
-  **Valor agregado de compras**: *O desconto será aplicado caso o valor somado das compras realizadas pelo cliente atinja o valor requerido*
-  **Valor do item**: *O desconto será aplicado caso o valor do item esteja dentro do limite configurado pela loja*
-  **Grupo de clientes**: *O desconto será aplicado caso o cliente esteja dentro do grupo de clientes criado pelo seller, é importante que o nome adicionado ao grupo seja exatamente igual ao nome no pedido para que a configuração funcione corretamente*
-  **Validação por número do cartão**: *O desconto será aplicado apenas para os clientes que pagarem com cartões das bandeiras definidas*
-  **CEP de destino**: *O desconto será aplicado caso o CEP de destino do cliente esteja dentre os selecionados pela loja*
- **Método de envio**: *O desconto será aplicado quando o método de envio escolhido pelo cliente se enquadre nos métodos escolhidos. Esse tipo de promoção só é válida para descontos de frete, como desconto nominal ou percentual de envio ou frete grátis*
- **Aplicar desconto somente para a modalidade de envio mais barata**: *Irá aplicar os descontos no valor do frete somente se a modalidade de envio selecionada for a mais barata. Essa opção é aplicada por padrão, mas pode ser desativada pelo seller. Esse tipo de promoção só é válida para descontos de frete, como desconto nominal ou percentual de envio ou frete grátis*
- **Método de pagamento**: *A promoção será aplicada caso o método de pagamento escolhido pelo cliente seja o mesmo selecionado pelo seller*
- **Número de parcelas**: *O desconto será aplicado caso o número de parcelas selecionado pelo cliente esteja dentro do limite definido*
-  **UTM Source**: *O desconto será aplicado caso a origem da UTM do cliente esteja dentro das origens definidas*
-  **Primeira compra**: *O desconto será aplicado apenas para os clientes que não efetuaram outros pedidos anteriormente*

## Restrições e limitações de uso

Conjunto de regras que determinam a aplicabilidade da promoção dentro da loja

- **Quantas vezes a promoção poderá ser usada**: *Quando não selecionado o campo **ilimitado** um campo é disponibilizado para definir o limite de aplicações para a promoção. Uma vez criada a promoção está condição somente deverá ser aplicada aos pedidos realizados a partir da data de criação dessa configuração, não devendo afetar os pedidos feitos anteriormente*
-  **Quantas vezes a promoção poderá ser usada por cliente**: *Define a restrição de utilização da promoção por cliente, não relacionada à restrição global. Caso seja definido um limite geral para a loja este limite deve ser priorizado em relação ao limite por cliente*
- **Quantidade máxima de itens afetados por carrinho**: *Define quantos itens presentes no carrinho serão afetados pela promoção*
- **Permitir promoções cumulativas**: *Permite a aplicação de mais de uma promoção com o mesmo tipo de desconto serem aplicadas simultaneament*
-  **Permitir que a promoção seja cumulativa com preços manuais**: *Define a possibilidade de acumular os benefícios da promoção em itens cujos preços tenham sido alterados manualmente por um operador de call-center*

