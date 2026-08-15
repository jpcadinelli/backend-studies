# E-commerce — Projeto Evolutivo

Este é o projeto prático central do roadmap. Ele começa pequeno e evolui conforme novos conceitos de backend são estudados.

## Regra principal

**Não implemente funcionalidades futuras antecipadamente.** Cada etapa deve partir do estado deixado pela etapa anterior.

O objetivo é sentir os problemas antes de estudar as soluções. Exemplo: os dados começam em memória para que a necessidade de persistência fique concreta antes do módulo de banco de dados.

## Domínio disponível ao longo do roadmap

Os conceitos podem surgir gradualmente:

- `Product` — produto do catálogo;
- `Customer` — cliente;
- `Cart` — carrinho;
- `Order` e `OrderItem` — pedido e itens;
- `Inventory` — estoque;
- `Payment` — pagamento simulado.

Isso não significa que todos devem existir desde o início.

## Evolução esperada

| Módulo | Evolução do projeto |
|---|---|
| 01 | Nenhuma implementação; fundamentos para entender a comunicação |
| 02 | Primeira API e catálogo em memória |
| 03 | Persistência em PostgreSQL |
| 04 | Pedido, itens e estoque com transações |
| 05 | Suíte de testes para proteger o comportamento existente |
| 06 | Refatoração arquitetural sem mudar comportamento |
| 07 | Melhorias locais de design e dependências |
| 08 | Modelagem explícita das regras do domínio |
| 09 | Clientes, login e permissões de cliente/admin |
| 10 | Hardening e correção de vulnerabilidades |
| 11 | Concorrência na compra da última unidade e tarefas assíncronas |
| 12 | Cache do catálogo com Redis |
| 13 | Evento de pedido criado e consumidor assíncrono |
| 14 | Idempotência, retries e falhas parciais |
| 15 | Logs, métricas e tracing |
| 16 | Medição, load test e otimização de gargalos |
| 17 | Containerização completa da aplicação |
| 18 | Pipeline automatizado |
| 19 | Deploy em cloud usando um provedor como referência |
| 20 | Revisão e desenho da arquitetura em escala |

## Stack de referência dos laboratórios

A stack serve apenas para concretizar os conceitos:

- Python + FastAPI para a API;
- PostgreSQL para persistência relacional;
- Redis quando cache for estudado;
- um broker de mensagens será escolhido no módulo de mensageria;
- Docker/Compose como apoio local e, posteriormente, objeto de estudo;
- ferramentas de observabilidade entram apenas no módulo correspondente.

A teoria dos módulos deve continuar aplicável a outras linguagens e tecnologias.

## Estado do projeto

O diretório não contém implementação inicial propositalmente. A primeira aplicação será criada no módulo **02 — APIs e Contratos**.
