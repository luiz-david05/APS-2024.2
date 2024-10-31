# Caso de Uso: Realizar Pedido (Pizzaria)

- **Atores Principais**: Cliente, Atendente
- **Descrição**: O cliente realiza um pedido, podendo ser assistido pelo atendente. O pedido pode ser para retirada ou entrega.
- **Pré-condições**: O cliente deve estar logado no sistema (se aplicável).
  
## Fluxo Principal
1. O cliente acessa a seção de pedidos (ou solicita ao atendente).
2. O sistema exibe o menu de pizzas e opções adicionais.
3. O cliente (ou atendente) escolhe os itens do menu e adiciona ao carrinho.
4. O cliente (ou atendente) finaliza o pedido.
5. O sistema gera o resumo do pedido e calcula o valor total.

- **Pós-condições**: O pedido é registrado e fica pendente de pagamento.

## Fluxo Alternativo
- **[A1] Modificar Pedido**: Caso o cliente deseje alterar o pedido antes de finalizá-lo, ele pode adicionar ou remover itens até a confirmação final.