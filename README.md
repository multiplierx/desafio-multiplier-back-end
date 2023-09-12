<p align="center">
  <img src="images/logo.png" width="320" alt="Multiplier Logo" />
</p>

# Desafio Back-end Multiplier

O intuito deste teste é avaliar seus conhecimentos técnicos de back-end. O teste consiste em fazer um sistema CRUD para um gerenciamento de clientes, com validação de CNPJ para pessoas jurídicas através de uma API externa.

Este desafio deve ser feito por você em sua casa. Gaste o tempo que você quiser, mas nos conte o tempo que levou para realizar o desafio.

## Instruções de entrega do desafio

1. Primeiro, faça um fork deste projeto para sua conta no Github (crie uma se você não possuir).
2. Em seguida, implemente o projeto conforme as instruções a seguir, em seu clone local.
3. Por fim, envie via e-mail com o link do desafio, avisando quanto tempo levou para fazê-lo.

## Descrição do projeto

### Objetivo

Desenvolver um sistema CRUD para gerenciamento de clientes, com validação de CNPJ para pessoas jurídicas através de uma API externa. O CRUD deve ser uma API REST com autenticação via Bearer Token. O projeto deve conter um dashboard monolítico para visualização dos clientes, com proteção contra ataques CSRF.
### Requisitos

#### Clientes

- Campos Obrigatórios:
    - Nome Fantasia
    - CNPJ
    - Endereço
    - Cidade
    - Estado
    - País
    - Telefone
    - E-mail
    - Área de Atuação | CNAE
    - Quadro Societário (se disponível)

#### CRUD de Clientes

- **Create**: Adicionar novos clientes
- **Read**: Listar e visualizar detalhes dos clientes
- **Update**: Atualizar informações dos clientes
- **Delete**: Remover clientes

#### Validação de CNPJ

- Utilizar uma API externa para validar o CNPJ de pessoas jurídicas, verificando tanto o formato quanto a existência e validade do CNPJ.
- Opções de API externa: Brasil API, ReceitaWS, Sintegra

#### API REST

- Desenvolver o CRUD em formato de API REST.
- Implementar autenticação via Bearer Token.
- Implementar tratamento e retorno adequado de erros, garantindo uma boa experiência para o usuário e integração com outros sistemas.

#### Dashboard Monolítico

- Criar uma interface web utilizando Blade do Laravel para visualização resumida dos clientes.
- Exibir informações como quantidade total de clientes cadastrados.
- Implementar filtros por Estado, Cidade, País e Área de Atuação.
- Implementar proteção contra ataques CSRF.

### Obrigatórios

- Documentação detalhada (principalmente para iniciar o projeto e para a API)
- Utilização de Docker
- Utilização de Git com commits convencionais
- Banco de dados: MySQL ou MariaDB
- Proteção contra ataques de injeção SQL
- Implementação de cache para otimização de consultas ao banco de dados
- Uso de migrations e seeders para estruturação e população inicial do banco de dados

### Diferenciais

- Rate limiting na API
- Testes unitários e de integração robustos
- Clean Code avançado
- Boas práticas avançadas de Laravel
- Adesão completa às PSR's
- Implementação de recursos adicionais, como paginação, filtragem e ordenação na listagem de clientes.


### Tecnologias

- Laravel
- Docker
- MySQL ou MariaDB
- Git
- Bearer Token para autenticação

### Entrega

- O código deve ser hospedado em um repositório Git privado, garantindo a segurança do código.
- Incluir um `README.md` detalhado com instruções para instalação, uso e detalhes da API.

### Desafio Extra

Pense em um cenário onde a API externa para validação de CNPJ falhe ou esteja indisponível. Como seu sistema se comportaria? Desenvolva uma solução alternativa para garantir que o sistema continue funcionando, mesmo que de forma limitada, durante essas falhas.
## Avaliação

1. Sua aplicação preenche os requerimentos básicos?
2. Você documentou a maneira de configurar o ambiente e rodar sua aplicação?
3. Você seguiu as instruções de envio do desafio?
4. Boas práticas RestFull
5. Boas práticas Laravel
6. Clean Code
7. Performance consultas

## Boa sorte!