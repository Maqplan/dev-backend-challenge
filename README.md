# Teste desenvolvedor back-end

## API para cadastro de lançamentos financeiros

### Crud de lançamentos

Cadastro de despesas e receitas e seus relacionamentos.

    - Descrição

    - Valor

    - Status (Em aberto, quitado, pago)

    - Data vencimento

    - Data pagamento

    - Categoria (id da categoria)

    - Pessoa (id da pessoa)

    - Tipo (debito/credito)

### Crud de pessoa

Pessoa que poderá ser vinculada ao lançamento e se será pessoa física ou jurídica.

    - Nome

    - CPF/CNPJ

    - Tipo de pessoa

### Crud de categorias

Tipo de lançamento, ex: Conta de água, Salário etc.

    - Descrição

    - Tipo (debito/credito)

### Recomendações

<hr>

- Usar algum banco de dados relacional ou MongoDB.
- Se usar banco de dados relacional, deixar algum script de criação do banco, e caso use MongoDB acesso ao Mongo Atlas.
- Os lançamentos financeiros deverão ter relacionamentos com pessoa e categorias.

### Diferênciais

<hr>

- Aplicar TDD e ter no mínimo 70% de cobertura em testes, de preferência usando JEST. Você pode encontrar ajuda com esse assunto [aqui]().
- Usar práticas e conceitos Clean Code. Você pode encontrar ajuda com esse assunto [aqui](https://github.com/Maqplan/dev-backend-challenge/blob/main/helpers/Apresenta%C3%A7%C3%A3o%20geral.pdf).
- Script docker para imagem do banco de dados.
- Documentação da API. ( De preferência Swagger )
- Interface visual básica para testar a aplicação, ou usando as [seguintes recomendações](https://github.com/Maqplan/dev-frontend-challenge).
