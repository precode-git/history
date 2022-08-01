# SKU Service
Um serviço é um item, opcional e com custo, que pode vir acompanhando um produto. 
A função do SKU Service é atribuir o valor de adicional de serviço aos itens da venda, esses serviços podem variar de embalagens de presente, montagem e até personalização. 
Ele será atrelado a um produto comprado e será exibido para o cliente durante o fluxo de pedido, na tela que achar melhor (produto, carrinho ou pedido).

Os detalhes de tipo de serviço e valor serão cadastrado nas tabelas SKU Service Type e SKU Service Value, respectivamente.

Opcionalmente um Serviço pode conter um anexo, caso o serviço contenha customizações opcionais.
Nesses casos o Anexo deve ser associado através do Identificador de Anexo (AttachmentId)

Um exemplo claro seria a venda de móveis, que muitas vezes precisam do serviço de montagem, o cliente pode optar por contratar ou não o serviço, e caso contrate o valor atribuído ao serviço precisa ficar atrelado ao produto específico.

