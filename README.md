<h1 align="center">FórumHub - API REST em Java com Spring Boot</h1>

<h4> FórumHub é uma API REST desenvolvida em Java com Spring Boot. 
O projeto tem como objetivo criar um sistema para gerenciamento de tópicos, 
implementando as operações básicas de CRUD (Create, Read, Update, Delete), 
além de autenticação e autorização usando Spring Security e JWT. </h4>

<p align="center">Challenge Alura + Oracle - ONE</p>
<p align="center">
<img alt="Badge do projeto" src="./assets/badgeForumHub.png" width="50%">
</p>


## Funcionalidades
- **Criar um Tópico:**  Permite que um usuário autenticado crie novos tópicos no fórum.
- **Listar Todos os Tópicos:** Exibe todos os tópicos registrados no sistema.
- **Exibir um Tópico Específico:** Recupera os detalhes de um tópico a partir do seu identificador único.
- **Atualizar um Tópico:** Permite que um usuário autenticado atualize as informações de um tópico.
- **Deletar um Tópico:** Remove um tópico do sistema de forma definitiva.
- **Autenticação e Autorização:** Protege as rotas da API com autenticação baseada em Spring Security e geração de tokens JWT.


## 🚀 Tecnologias
- **JAVA**
- **Spring Framework:**
    - **Spring Web:** Para criação de endpoints REST.
    -  **Spring Data JPA:** Para gerenciamento das entidades e operações com o banco de dados.
    -  **Spring Security:** Para autenticação e autorização de usuários.
- **JWT (JSON Web Token):** Para gerenciamento de sessões e autenticação segura.
- **MySql** - Banco de dados relacional usado para persistência dos dados.
- **Maven** - Para gerenciamento de dependências e automação de build.
- **Swagger:** Ferramenta usada para explorar todos os endpoints da API, e disponibilizar uma documentação interativa e acessível da API REST.

## Endpoints 
### Autenticação 
- **POST/auth/login**
- Faz login e retorna um token JWT para autenticação.

![Imagem autenticação ](/assets/autenticacao.png)

### Tópicos
![Imagem tópicos ](/assets/topicos.png)


## Contato
- murilopizolito@gmail.com
