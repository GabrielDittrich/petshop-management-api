# Projeto PetShop API
Este projeto consiste em uma API para um sistema de gerenciamento de um PetShop, desenvolvida em C# utilizando o framework .NET.<br>
A API se comunica com um banco de dados MySQL e está integrada com um front-end em React.

# Funcionalidades
<b>Swagger</b>: Documentação da API disponível para visualização em http://localhost:xxxx/swagger/index.html, facilitando o teste dos endpoints.<br><br>
<b>CORS</b>: Configuração para permitir solicitações do front-end hospedado em http://localhost:3000.<br><br>
<b>Banco de Dados</b>: Conexão com o MySQL, utilizando Entity Framework para gerenciar os dados.<br><br>
<b>React Router</b>: Navegação entre os componentes.<br><br>
<b>Axios: é uma biblioteca JavaScript que permite fazer requisições HTTP em navegadores e servidores Node.js de forma mais dinâmica <br><br>

# Modelos
## Pessoa: Representa as informações dos clientes, contendo os campos:
- Id: Identificador único.
- Nome: Nome do cliente.
- Telefone: Número de telefone.
- Email: Endereço de e-mail.

## Produto: Representa os produtos disponíveis no PetShop, contendo os campos:
- Id: Identificador único.
- NomeProduto: Nome do produto.
- Descricao: Descrição do produto.
- Preco: Preço do produto.

## Animal: Representa os animais disponíveis para adoção, contendo os campos:
- Id: Identificador único.
- NomeAnimal: Nome do animal.
- Raca: Raça do animal.
- Porte: Porte do animal (pequeno, médio, grande).

## Antes de executar o projeto, você precisará ter instalado:
- .NET SDK (versão X.X ou superior)
- MySQL Server
- MySQL Workbench (opcional, para gerenciar o banco de dados)

# Instalação

Clone o repositório:
- git clone <URL do repositório>
- cd <nome do repositório>

## Restaure as dependências do projeto:
### Parte C#:
Configure o banco de dados MySQL.<br>
Crie um banco de dados mysql com o nome que preferir e configure a string de conexão no Program.cs com suas credenciais. <br>

Execute a aplicação:
- dotnet run

### Parte React:
- npm install

Execute a aplicação:
- npm start
Acesse a documentação da API pelo Swagger em http://localhost:xxxx/swagger/index.html.

# Endpoints
GET /: Retorna uma mensagem de boas-vindas para o PetShop.
Mapeamento de APIs: Endpoints para gerenciar pessoas, produtos e animais.
