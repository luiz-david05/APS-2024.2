# Caso de Uso: Remover Comentário (Blog)

- **Ator Principal**: Dono do Blog (Administrador)
- **Descrição**: O administrador remove comentários considerados inapropriados ou que violam as diretrizes do blog.
- **Pré-condições**: O administrador deve estar autenticado no sistema.
  
## Fluxo Principal
1. O administrador acessa a área de comentários da postagem.
2. O sistema exibe todos os comentários, com a opção de exclusão para cada um.
3. O administrador seleciona um comentário para remover.
4. O sistema exclui o comentário da postagem.

- **Pós-condições**: O comentário é removido do blog.

## Fluxo Alternativo
- **[A1] Comentário Inexistente**: Se o comentário já tiver sido removido ou não existir, o sistema exibe uma mensagem de erro.