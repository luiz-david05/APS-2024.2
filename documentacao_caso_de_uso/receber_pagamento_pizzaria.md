# Caso de Uso: Receber Pagamento (Pizzaria)

- **Ator Principal**: Atendente
- **Descrição**: O atendente recebe o pagamento do pedido feito pelo cliente, com opções de método de pagamento (cartão, dinheiro ou outros).
- **Pré-condições**: O pedido deve estar registrado e pendente de pagamento.
  
## Fluxo Principal
1. O atendente acessa a funcionalidade de recebimento de pagamento.
2. O sistema exibe as opções de pagamento disponíveis (cartão, dinheiro ou outros).
3. O cliente escolhe o método de pagamento.
4. O atendente confirma o recebimento do pagamento.
5. O sistema atualiza o status do pedido como pago.

- **Pós-condições**: O pedido é registrado como pago e é liberado para retirada ou entrega.

## Fluxo Alternativo
- **[A1] Erro no Pagamento**: Se o pagamento for recusado (por falha do cartão ou outros motivos), o sistema exibe uma mensagem de erro e o pedido permanece pendente até nova tentativa.