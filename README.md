# Cadastro de Usuários com Spring Boot

Projeto acadêmico de Gilberto Antonio Corrêa Filho para cadastrar e listar usuários com Java, Spring Boot, JPA e PostgreSQL. Inclui menu interativo no terminal e endpoints GET e POST em `/usuarios`.

## Executar

Requer JDK 17 ou superior e PostgreSQL acessível. Configure `DB_URL` (URL JDBC), `DB_USERNAME` e `DB_PASSWORD` no ambiente. Não inclua credenciais no repositório.

```sh
sh mvnw spring-boot:run
```

O menu permite cadastrar e listar usuários. A opção 0 encerra o menu; para encerrar o servidor, use Ctrl+C.

## API

- GET /usuarios: lista usuários.
- POST /usuarios: cadastra um usuário com JSON `{"nome":"Maria"}`.

As versões de dependências do projeto original foram preservadas. Compilação e empacotamento validados com `sh mvnw -DskipTests package`. Testes de integração com PostgreSQL não foram executados.

