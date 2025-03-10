# API de Agenda de Contatos
Esta é a documentação de requisitos para a API de Agenda de Contatos. Esta API permite aos usuários gerenciar contatos, categorizá-los e
realizar operações de CRUD.

## Funcionalide 
- Os usuários devem poder adicionar novos contatos com informações como nome, número de telefone, endereço de e-mail, etc.

## Requisitos Funcionais

- [ ] Cadastro de Contatos
- [ ] Visualização de Contatos
- [ ] Atualização de Contatos
- [ ] Exclusão de Contatos

## Requisitos de Autenticação e Autorização

- [ ] Autenticação de Usuários
- [ ] Autorização de Acesso às Operações
- [ ] Criação de usuário

## Regras de Negócios
- Os usuários devem ser cadastrados com nome e e-mail.
- O e-mail deve ser uma chave única.
- Os contatos devem conter pelo menos um nome e uma forma de contato (número de telefone, endereço de e-mail, etc).
- Somente usuários autenticados podem executar operações de criação, atualização e exclusão de contatos.
- A autorização é baseada em funções de usuário, como administrador e usuário regular.
- Todos os dados da API devem ser armazenados de forma segura e protegidos contra acesso não autorizados.
- As entradas do usuário devem ser validadas para evitar à inserção de dados incorretos ou maliciosos.
