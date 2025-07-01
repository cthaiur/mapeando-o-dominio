# Sistema de Gerenciamento de Estoque

Este repositório contém a análise inicial de requisitos baseada em uma conversa entre um **Domain Expert** e um **Desenvolvedor**, com o objetivo de identificar as **entidades de domínio** e os **casos de uso** de um sistema de gerenciamento de estoque.

## Entidades de Domínio

| Entidade         | Descrição |
|------------------|-----------|
| **Produto**       | Representa um item do estoque, contendo atributos como: ID, nome, tamanho, cor, quantidade em estoque, quantidade mínima, etc. |
| **Estoque**       | Representa o controle de entrada e saída de produtos. Inclui histórico de movimentações. |
| **Venda**         | Registra a venda de produtos, incluindo data, quantidade, valor e lucro. |
| **Alerta**        | Notificações geradas automaticamente quando um produto atinge seu limite mínimo de estoque. |
| **Ordem de Compra** | Representa pedidos de reposição de estoque. Pode ser criada manualmente ou de forma automática. |
| **Fornecedor**    | Representa os fornecedores vinculados aos produtos. Armazena informações como nome, prazo de entrega e produtos fornecidos. |

## Casos de Uso

| Caso de Uso | Descrição |
|-------------|-----------|
| **Cadastrar/gerenciar produtos** | Criar, editar e excluir produtos no sistema. |
| **Rastrear movimentações de estoque** | Visualizar entradas e saídas de produtos, com base em identificadores únicos. |
| **Definir quantidade mínima de estoque** | Configurar limites mínimos para cada produto. |
| **Emitir alertas de estoque baixo** | Gerar notificações por e-mail e no sistema quando o estoque atinge o limite mínimo. |
| **Visualizar histórico de vendas** | Consultar produtos vendidos por período, lucro por produto, etc. |
| **Visualizar histórico de estoque** | Ver variações no estoque ao longo do tempo para análise de tendências. |
| **Gerar relatórios analíticos** | Relatórios de desempenho de vendas e movimentações de estoque. |
| **Criar e gerenciar ordens de compra** | Gerenciar pedidos de reposição, incluindo criação automática com base em regras. |
| **Integrar com fornecedores** | Receber atualizações sobre prazos de entrega de forma automatizada. |
| **Receber notificações automáticas** | Alerta para usuários do sistema sobre estoque baixo ou atualizações de pedidos. |



