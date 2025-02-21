# Esquema de Integração de Disciplinas

## 1. Visão Geral do Projeto
O projeto consiste na integração de três disciplinas para desenvolver um sistema completo utilizando diferentes tecnologias e paradigmas. O sistema será composto por:
- **Uma API desenvolvida em NodeJS** (Disciplina: Tópicos Especiais), responsável pela lógica de negócio e comunicação com o banco de dados.
- **Um gerador de dados em Java** (Disciplina: Desenvolvimento de Software), que simula informações e as insere no banco de dados da API.
- **Um sistema web em PHP** (Disciplina: Desenvolvimento de Sistemas), que fornece a interface para os usuários e consome os serviços da API.

## 2. Estrutura do Projeto
### a) API NodeJS (Tópicos Especiais)
- Desenvolvida utilizando **Express.js**
- Gerencia **CRUD** de dados
- Autenticação utilizando **JWT**
- Conexão com **Banco de Dados MySQL/PostgreSQL**
- Exposição de endpoints RESTful

### b) Gerador de Dados em Java (Desenvolvimento de Software)
- Aplicação console para gerar registros aleatórios
- Utiliza **Java + JDBC** para inserir dados no banco da API
- Implementação de **POO (Programação Orientada a Objetos)**
- Possível uso de bibliotecas como **Faker** para geração de dados fictícios

### c) Sistema Web em PHP (Desenvolvimento de Sistemas)
- Desenvolvido utilizando **PHP + HTML/CSS/JavaScript**
- Consumo da API via **cURL ou bibliotecas HTTP (ex: Guzzle)**
- Sistema de login e autenticação via JWT
- Renderização dinâmica de dados vindos da API
- Interface responsiva utilizando **Bootstrap** ou outra biblioteca CSS

## 3. Fluxo de Funcionamento
1. **A API (NodeJS) é desenvolvida** para gerenciar os dados e fornecer endpoints REST.
2. **O gerador de dados (Java) cria dados fictícios** e insere no banco de dados da API.
3. **O sistema web (PHP) consome os endpoints da API**, exibe as informações e permite a interação do usuário.

## 4. Tecnologias Utilizadas
| **Componente**       | **Tecnologia**      |
|----------------------|---------------------|
| API                  | NodeJS + Express.js |
| Banco de Dados       | MySQL/PostgreSQL    |
| Gerador de Dados     | Java + JDBC         |
| Frontend/Backend Web | PHP + HTML/CSS/JS   |
| Autenticação         | JWT                 |

## 5. Benefícios da Integração
- Aplicação prática dos conteúdos vistos em cada disciplina
- Trabalho colaborativo entre os alunos
- Aprendizado sobre integração de tecnologias
- Desenvolvimento de um sistema realista e funcional

