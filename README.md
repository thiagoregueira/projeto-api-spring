# API do Projeto
Esta é a documentação da API do projeto. Aqui você encontrará informações sobre as principais funcionalidades e como utilizá-las.

## Sobre o Projeto
O projeto é uma API desenvolvida em Java que oferece uma série de funcionalidades para gerenciamento de dados de clientes.

### Funcionalidades

#### Boas-vindas
Endpoint: /boasVindas/{nome} Método: GET

Descrição: Retorna uma mensagem de boas-vindas personalizada com o nome do usuário.

#### Mensagem
Endpoint: `` Método: GET

Descrição: Retorna uma mensagem de "Hello World!".

#### Status
Endpoint: /status Método: GET

Descrição: Retorna um código de status HTTP 201 (Created).

#### Contador
Endpoint: /api/contador Método: GET

Descrição: Retorna o número total de registros presentes na API.

#### Soma de Idades
Endpoint: /api/somaIdades Método: GET

Descrição: Retorna a soma das idades de todos os clientes cadastrados.

#### Listar Clientes
Endpoint: /cliente Método: GET

Descrição: Retorna a lista de todos os clientes cadastrados.

#### Cadastrar Cliente
Endpoint: /cliente Método: POST

Descrição: Cadastra um novo cliente na API.

#### Selecionar Cliente pelo Código
Endpoint: /cliente/{codigo} Método: GET

Descrição: Retorna os detalhes de um cliente específico com base no código fornecido.

#### Editar Cliente
Endpoint: /cliente/{codigo} Método: PUT

Descrição: Edita os detalhes de um cliente específico com base no código fornecido.

#### Remover Cliente
Endpoint: /cliente/{codigo} Método: DELETE

Descrição: Remove um cliente específico com base no código fornecido.

#### Ordenar por Nomes
Endpoint: /api/ordenarNomes Método: GET

Descrição: Retorna a lista de clientes ordenada por nomes.

#### Ordenar por Idade
Endpoint: /api/ordenarIdade Método: GET

Descrição: Retorna a lista de clientes ordenada por idade.

#### Nome Contém
Endpoint: /api/nomeContem Método: GET

Descrição: Retorna a lista de clientes cujo nome contém uma determinada sequência de caracteres.

#### Inicia com
Endpoint: /api/iniciaCom Método: GET

Descrição: Retorna a lista de clientes cujo nome começa com uma determinada sequência de caracteres.

#### Termina com
Endpoint: /api/terminaCom Método: GET

Descrição: Retorna a lista de clientes cujo nome termina com uma determinada sequência de caracteres.

### Como Utilizar
Para utilizar a API, você deve fazer requisições HTTP para os endpoints descritos acima. Por exemplo, para cadastrar um novo cliente, você deve enviar uma requisição HTTP POST para o endpoint /cliente com os dados do cliente no corpo da requisição.

### Dependências
O projeto utiliza as seguintes dependências:

Spring Boot
Hibernate
MySQL

### Como Executar
Para executar o projeto, siga os seguintes passos:

Clone o repositório para sua máquina local.
Configure as dependências e o banco de dados de acordo com o arquivo application.properties.
Execute a classe ApiApplication para iniciar o servidor.

