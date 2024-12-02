# Banco de Dados

## O sistema de biblioteca é separado em três tabelas, utilizando a tecnologia do DataVerse(Banco de dados Microsoft)

### Livros

| Nome                  | Tipo    |
| --------------------- | ------- |
| Titulo                | Texto   |
| ISBN                  | Texto   |
| Editora               | Texto   |
| Sinopse               | Texto   |
| Edição                | Texto   |
| Data Inclusão         | Date    |
| Disponível            | Boleean |
| Aguardando Empréstimo | Boleean |
| Empréstimo Efetuado   | Boleean |
| Email Posse           | Texto   |

### Multas

| Nome         | Tipo  |
| ------------ | ----- |
| Email        | Texto |
| Valor        | Float |
| Data Emissão | Date  |

### Usuários

| Nome      | Tipo    |
| --------- | ------- |
| Email     | Texto   |
| Cargl     | Texto   |
| Bloqueado | Boleean |
