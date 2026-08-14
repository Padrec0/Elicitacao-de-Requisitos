1. Cliente acompanhando o pedido
História de usuário

Como cliente, quero acompanhar meu pedido depois que fizer a compra, para saber se o restaurante já começou a preparar, se o pedido está pronto e quando ele deve chegar.
Dado que eu fiz um pedido, Quando eu acessar a área de acompanhamento, Então devo conseguir ver o status atual do meu pedido.
Dado que o status do meu pedido foi atualizado, Quando eu acessar o acompanhamento, Então devo conseguir ver a nova situação do pedido.
Dado que meu pedido já saiu para entrega, Quando eu acessar o acompanhamento, Então devo conseguir ver uma previsão de quando ele chegará.

2. Restaurante
Como gestor, quero pausar um item no painel para evitar vendas sem estoque. Dado que pausei o item, quando o cliente abre o cardápio, então o prato aparece "Esgotado". Dado que o cliente tenta adicionar um item pausado, quando clica em comprar, então o app bloqueia e avisa do esgotamento. Dado que reativei o item, quando salvo no painel, então ele volta a ficar disponível no app.

3. Entregador
Como entregador, quero reportar imprevistos pelo app para resolver a rota rapidamente. Dado que estou em rota, quando clico em "Reportar problema", então vejo opções rápidas de imprevistos. Dado que escolhi "Cliente não atende", quando confirmo, então o cliente é avisado e inicia um timer na minha tela. Dado um problema grave (veículo quebrou), quando envio o relato, então a rota é cancelada para mim e reatribuída.

MoSCoW
A necessidade 1 entra como Must Have por ser essencial no pós-venda para não sobrecarregar o suporte. A necessidade 2 fica como Should Have para evitar cancelamentos e estornos por falta de ingrediente. A necessidade 3 roda como Could Have, pois no início o suporte direto resolve os imprevistos da rota. Como Won't Have, deixamos de fora chamadas de voz no app, focando apenas em avisos por texto.