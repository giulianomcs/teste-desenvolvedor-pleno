# Teste Técnico: Desenvolvedor Full Stack (C# / React)

![image](https://github.com/user-attachments/assets/b7fde9b9-5285-48b2-85c7-222db008933c)

Bem-vindo(a) ao teste para a vaga de Desenvolvedor Full Stack Pleno! Aqui você poderá demonstrar suas habilidades técnicas e seu conhecimento no desenvolvimento de aplicações integradas.

---

## O Desafio

O objetivo é criar uma aplicação para gestão de produtos. A solução deverá incluir:

1. Uma API RESTful em **C#** para gerenciar o cadastro e operações de produtos.
2. Uma interface web em **React** que permita interações com a API.

A solução deve refletir boas práticas de desenvolvimento e design.

---

## Requisitos Obrigatórios

### Backend

1. **CRUD de Produtos**:
   - Implementar as operações de criação (POST), leitura (GET - individual e lista), atualização (PUT) e exclusão (DELETE) para produtos.
   - O **DELETE** deve ser apenas lógico, ou seja, os produtos excluídos não devem ser removidos do banco de dados, mas sim marcados como inativos (ex.: campo `isDeleted`).

2. **Relacionamento entre Tabelas**:
   - Estruturar as tabelas com os seguintes relacionamentos:
     - **Categoria do Produto**:
       - Uma tabela de categorias que contenha campos como `id`, `nome` e `descricao`. Cada produto deve estar associado a uma categoria.
       - Os dados de categorias devem ser previamente populados na inicialização do banco. Por exemplo: "Eletrônicos", "Móveis", "Alimentos".
     - **Fornecedor**:
       - Uma tabela de fornecedores que contenha campos como `id`, `nome`, `cnpj`, `telefone` e `endereco`. Cada produto pode estar associado a um ou mais fornecedores.
       - Os dados de fornecedores também devem ser previamente populados na inicialização do banco com dados fictícios, mas plausíveis.

3. **Autenticação**:
   - Adicionar um mecanismo de autenticação básico (JWT, por exemplo) para proteger os endpoints da API.

4. **Banco de Dados**:
   - Utilize um banco relacional (MySQL, SQL Server, Informix).

### Frontend

1. **Listagem de Produtos**:
   - Exibir os produtos cadastrados em uma tabela responsiva, incluindo informações de categoria e fornecedores.

2. **Cadastro e Edição de Produtos**:
   - Formulário para criar e editar produtos, com opção de selecionar a categoria e fornecedores.

3. **Validações**:
   - Implementar validação básica dos campos no frontend.

4. **Exclusão de Produtos**:
   - Possibilidade de excluir um produto da listagem.

---

## Requisitos Não Obrigatórios (Extras)

1. **Documentação**: Documentar a API utilizando Swagger ou similar.
2. **Testes Automatizados**:
   - Backend: testes unitários e/ou de integração utilizando xUnit.
   - Frontend: testes unitários ou de interface com Jest.
3. **Design**: Melhorar a interface com boas práticas de UX/UI.
4. **Desempenho**: Implementar cache para melhorar a performance de requisições no backend.

---

## Requisitos Técnicos

### Tecnologias Permitidas

- **Backend**: C#, .NET Core / .NET 6+
- **Frontend**: React com TypeScript
- **Banco de Dados**: Relacional (MySQL, SQL Server, Informix)

### Tecnologias Não Permitidas

- Bancos de dados não relacionais
- Frameworks de backend que não sejam em C#
- Bibliotecas que implementem diretamente o CRUD

---

## Entrega

1. **Fork do Repositório**: Faça um fork deste repositório para sua conta do GitHub.
2. **Branch**: Crie uma branch com o nome `teste/[SEU NOME]` (por exemplo: `teste/joao-silva`).
3. **Pull Request**: Ao finalizar, faça um pull request com a sua branch.
4. **Documentação**: Inclua no `README.md` do repositório:
   - Como configurar e rodar o projeto
   - Tecnologias utilizadas
   - Decisões de design

---

## Avaliação

### Critérios

- Qualidade do código e organização do projeto
- Implementação de boas práticas (design patterns, SOLID, etc.)
- Alinhamento com os requisitos solicitados
- Documentação clara

Boa sorte! Estamos animados para conhecer seu trabalho.
