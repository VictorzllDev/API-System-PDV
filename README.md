# API-System-PDV

## Visão Geral

A **API-System-PDV** é uma API projetada para o gerenciamento de vendas e usuários no APP **System-PDV**, que é destinado a pontos de venda (PDV), como caixas de supermercados e estabelecimentos similares. Esta API facilita a administração centralizada das operações de venda, permitindo o gerenciamento eficiente de caixas, administradores e dados de vendas.

Repositório do aplicativo **System-PDV**: [System-PDV Repository](https://github.com/VictorzllDev/System-PDV)

## Tecnologias Utilizadas

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)

## Estrutura do Projeto

- **/entities:** Modelos de dados que representam as entidades do sistema.
- **/repositories:** Lógica de negócios e interação com os modelos, organizados por funcionalidade.
- **/usecases:** Camada intermediária para operações complexas e regras de negócio.
- **/middlewares:** Funções de middleware para autenticação, autorização, e outras operações intermediárias.

## Funcionalidades

| Funcionalidade             | Descrição                                                        | Status        |
|----------------------------|------------------------------------------------------------------|---------------|
| **Login**                  | Autenticação de usuários com e-mail e senha                      | Em andamento  |
| **Registro de Usuários**   | Criação de novas contas de caixas e administradores              | Em andamento  |
| **Gerenciamento de Sessões** | Uso de JWT para sessões seguras e controle de acesso            | Em andamento  |
| **Registro de Vendas**     | APIs para registro de transações de venda                        | Planejado     |
| **Consulta de Vendas**     | Acesso a informações e histórico de vendas com filtragem         | Planejado     |
| **Relatórios de Vendas**   | Geração de relatórios de desempenho para análise de dados        | Planejado     |

## Estado do Projeto

**Status:** Em andamento.

O backend está em fase de implementação das funcionalidades básicas de autenticação e gestão de usuários. As funcionalidades de gerenciamento de vendas e relatórios estão planejadas para as próximas etapas do desenvolvimento.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões, correções ou melhorias, sinta-se à vontade para abrir um pull request.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.
