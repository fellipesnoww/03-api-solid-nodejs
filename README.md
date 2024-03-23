# APP

Gympass style App

## Requisitos Funcionais (O que a aplicação pode fazer)

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter dados do perfil do usuário;
- [ ] Deve ser possível obter os números de check-ins realizado pelo usuário logado;
- [ ] Deve ser possível o usuário obter o históricos de check-ins;
- [ ] Deve ser possível o usuário buscar academias próximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário realizar check-in em uma academia;
- [ ] Deve ser possível validar o check-in de um usuário;
- [ ] Deve ser possível cadastrar uma academia;

## Regras de Negocio (Caminhos que cada requisito pode tomar : Sendo sempre relacionada aos requisitos)

- [ ] O usuário não pode se cadastrar com um e-mail duplicado;
- [ ] O usuário não pode fazer dois check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in perto (100m) da academia;
- [ ] O check-in so pode ser válidado até 20 minutos após criado;
- [ ] O check-in so pode ser validado por administradores;
- [ ] A academia so pode ser cadastrada por administrados;

## Requisitos nao funcionais (Requisitos que nao partem do cliente, detalhes tecnicos)

- [ ] A senha do usuário precisa estar criptografada;
- [ ] Os dados da aplicação precisam estar persistidos em um banco PostgresSQL;
- [ ] Todas as listas de dados precisam estar paginadas 20 itens por página;
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token);