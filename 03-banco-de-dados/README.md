# 03 — Banco de Dados e Modelagem

## Objetivo
Entender persistência e modelagem de dados, usando PostgreSQL como implementação relacional de referência.

## Pré-requisitos
Módulos 01 e 02.

## Conteúdo
### Relacionais
- tabelas, linhas e colunas;
- SQL;
- PK, FK, UNIQUE, NOT NULL e CHECK;
- relacionamentos 1:1, 1:N e N:N;
- normalização em nível introdutório;
- índices e custo de consultas;
- modelagem orientada aos dados do problema.

### Não relacionais — visão geral
- por que existem modelos além do relacional;
- key-value, documentos, wide-column e grafos;
- diferenças de modelagem e acesso;
- exemplos: Redis, MongoDB, Cassandra e Neo4j.

Aprofundamentos em tecnologias não relacionais acontecem apenas quando o projeto precisar delas.

## Prática
Subir PostgreSQL com Docker Compose, aprender acesso básico e migrar produtos da memória para persistência.

## Evolução do e-commerce
Produtos passam a persistir. Clientes podem ser introduzidos. O projeto ganha seu primeiro modelo relacional.
