# Caso de Uso: Administrar Estoque (Loja de CDs)

- **Ator Principal**: Gerente
- **Descrição**: O gerente acessa o sistema para gerenciar o estoque de CDs, incluindo operações de cadastro, atualização e remoção de CDs disponíveis na loja.
- **Pré-condições**: O gerente deve estar autenticado no sistema (fazer login).
  
## Fluxo Principal
1. O gerente faz login no sistema.
2. O sistema exibe a opção de administrar o estoque.
3. O gerente seleciona a opção de administração de estoque.
4. O sistema apresenta a lista de CDs no estoque.
5. O gerente pode adicionar novos CDs, editar informações (preço, quantidade, descrição) ou remover CDs do estoque.
6. O sistema salva e atualiza o estoque conforme as alterações feitas pelo gerente.

- **Pós-condições**: O estoque é atualizado, refletindo as alterações realizadas pelo gerente.

## Fluxo Alternativo
- **[A1] Erro de Permissão**: Se um usuário sem permissão de gerente tentar acessar a administração de estoque, o sistema exibe uma mensagem de acesso negado.