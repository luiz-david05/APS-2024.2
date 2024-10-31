# Caso de Uso: Cadastrar Produtos (Pizzaria)

- **Ator Principal**: Gerente
- **Descrição**: O gerente acessa o sistema para cadastrar novos produtos, incluindo informações como nome, descrição, preço e quantidade inicial em estoque.
- **Pré-condições**: O gerente deve estar autenticado no sistema (fazer login).
  
## Fluxo Principal
1. O gerente faz login no sistema.
2. O sistema exibe a opção de cadastrar produtos.
3. O gerente seleciona a opção de cadastro de produtos.
4. O sistema solicita as informações do novo produto:
   - Nome do produto
   - Descrição
   - Preço
   - Categoria
   - Quantidade inicial em estoque
5. O gerente insere as informações necessárias.
6. O sistema valida as informações inseridas.
7. Se os dados estiverem corretos, o sistema adiciona o novo produto ao estoque.
8. O sistema confirma que o produto foi cadastrado com sucesso.

- **Pós-condições**: O novo produto é adicionado ao estoque, refletindo as informações cadastradas pelo gerente.

## Fluxo Alternativo
- **[A1] Erro de Validação**: Se houver informações faltando ou incorretas, o sistema exibe uma mensagem de erro solicitando correções.
- **[A2] Erro de Permissão**: Se um usuário sem permissão de gerente tentar acessar a opção de cadastrar produtos, o sistema exibe uma mensagem de acesso negado. 
```

Você pode copiar o texto acima e salvá-lo em um arquivo com a extensão `.md`. Se precisar de mais alguma coisa, é só avisar!