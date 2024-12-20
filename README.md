# Avaliação Física Backend

Avaliação Física Backend é uma aplicação backend para gerenciar avaliações físicas de usuários, permitindo operações CRUD (Create, Read, Update, Delete) para gerenciar usuários e suas avaliações físicas.

## Funcionalidades

- 🏋️‍♂️ Gerenciamento de usuários
- 📊 Gerenciamento de avaliações físicas
- 🔍 Operações CRUD para usuários e avaliações
- 🔒 Autenticação e segurança dos dados

## Tecnologias Utilizadas

- Node.js
- Express
- MySQL2
- MariaDB (opcional)
- Nodemon
- Dotenv
- ESLint
- Debug

## Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/avaliacao-fisica-backend.git
cd avaliacao-fisica-backend
```

2. Instale as dependências:

```bash
npm install
```

3. Configure as variáveis de ambiente:

Crie um arquivo `.env` na raiz do projeto e adicione as seguintes variáveis:

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=sua_senha
DB_NAME=db_avaliacao_fisica
```

4. Execute o projeto:

```bash
npm run dev
```

5. Abra o Insomnia ou qualquer cliente HTTP e use as seguintes rotas para interagir com a API:

### Rotas de Usuários

- **Criar Usuário (POST):**
  ```
  POST http://localhost:3000/usuarios
  ```

- **Obter Todos os Usuários (GET):**
  ```
  GET http://localhost:3000/usuarios
  ```

- **Obter Usuário por ID (GET):**
  ```
  GET http://localhost:3000/usuarios/:id
  ```

- **Atualizar Usuário por ID (PUT):**
  ```
  PUT http://localhost:3000/usuarios/:id
  ```

- **Deletar Usuário por ID (DELETE):**
  ```
  DELETE http://localhost:3000/usuarios/:id
  ```

### Rotas de Avaliações

- **Criar Avaliação (POST):**
  ```
  POST http://localhost:3000/avaliacoes
  ```

- **Obter Todas as Avaliações (GET):**
  ```
  GET http://localhost:3000/avaliacoes
  ```

- **Obter Avaliação por ID (GET):**
  ```
  GET http://localhost:3000/avaliacoes/:id
  ```

- **Atualizar Avaliação por ID (PUT):**
  ```
  PUT http://localhost:3000/avaliacoes/:id
  ```

- **Deletar Avaliação por ID (DELETE):**
  ```
  DELETE http://localhost:3000/avaliacoes/:id
  ```

## Aprendizados

Este projeto foi uma excelente oportunidade para:

- 🔷 Aprofundar conhecimentos em Node.js e Express
- 🔷 Praticar a integração com bancos de dados MySQL e MariaDB
- 🔷 Implementar operações CRUD
- 🔷 Configurar e utilizar variáveis de ambiente com Dotenv
- 🔷 Melhorar a qualidade do código com ESLint

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## Contato

**M Daniel Dantas**

- **GitHub:** [mdanieldantas](https://github.com/mdanieldantas)
- **LinkedIn:** [mdanieldantas](https://www.linkedin.com/in/mdanieldantas)
- **Portfólio:** [Portfólio de Daniel Dantas](https://danieldantasdev.vercel.app)
- **Email:** [contatomarcosdgomes@gmail.com](mailto:contatomarcosdgomes@gmail.com)
- **Link do Projeto:** [backend-avaliacao-fisica
](https://github.com/mdanieldantas/backend-avaliacao-fisica)
- **Currículo:** [Baixar Currículo](https://drive.google.com/file/d/1Z_tqBv6kg4wkDAQHAvY3lcuVSq3rabTt/view?usp=drive_link)