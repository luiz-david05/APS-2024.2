# Caso de Uso: Criar Postagem (Blog)

- **Ator Principal**: Administrador
- **Descrição**: O administrador acessa o sistema para criar novas postagens no blog, incluindo título, conteúdo e categorias.
- **Pré-condições**: O administrador deve estar autenticado no sistema (fazer login).

## Fluxo Principal
1. O administrador faz login no sistema.
2. O sistema exibe a opção de criar uma nova postagem.
3. O administrador seleciona a opção de criar postagem.
4. O sistema solicita as informações da nova postagem:
   - Título
   - Conteúdo
   - Categoria (opcional)
5. O administrador insere as informações necessárias.
6. O sistema valida as informações inseridas.
7. Se os dados estiverem corretos, o sistema salva a nova postagem.
8. O sistema confirma que a postagem foi criada com sucesso.

- **Pós-condições**: A nova postagem é publicada no blog e visível para os usuários.

## Fluxo Alternativo
- **[A1] Erro de Validação**: Se houver informações faltando ou incorretas, o sistema exibe uma mensagem de erro solicitando correções.
- **[A2] Erro de Permissão**: Se um usuário sem permissão de administrador tentar acessar a opção de criar postagens, o sistema exibe uma mensagem de acesso negado.