# Caso de Uso: Remover Postagem (Blog)

- **Ator Principal**: Administrador
- **Descrição**: O administrador acessa o sistema para remover postagens existentes do blog.
- **Pré-condições**: O administrador deve estar autenticado no sistema (fazer login).

## Fluxo Principal
1. O administrador faz login no sistema.
2. O sistema exibe a lista de postagens existentes.
3. O administrador seleciona a postagem que deseja remover.
4. O sistema solicita confirmação para a remoção da postagem.
5. O administrador confirma a remoção.
6. O sistema remove a postagem selecionada.
7. O sistema confirma que a postagem foi removida com sucesso.

- **Pós-condições**: A postagem é removida do blog e não está mais visível para os usuários.

## Fluxo Alternativo
- **[A1] Erro de Permissão**: Se um usuário sem permissão de administrador tentar acessar a opção de remover postagens, o sistema exibe uma mensagem de acesso negado.