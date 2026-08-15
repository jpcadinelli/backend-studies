# Exercícios — Banco de Dados e Modelagem

## Revisão
1. Qual problema de persistência existe na versão anterior do e-commerce?
2. Qual a diferença entre PK e FK?
3. Por que constraints pertencem também ao banco?
4. Quando um índice ajuda e qual custo ele pode introduzir?
5. Em que sentido um banco key-value difere de um relacional?

## Laboratório PostgreSQL
Siga `lab/README.md` para subir e acessar PostgreSQL.

## Implementação cumulativa
- criar um schema específico do projeto/módulo;
- modelar `products`;
- substituir armazenamento em memória por PostgreSQL;
- criar operações de leitura e escrita necessárias aos endpoints existentes;
- introduzir `customers` apenas se necessário para preparar os próximos passos;
- registrar as decisões de modelagem.

## Não fazer ainda
- transações complexas;
- Redis;
- ORM como forma de esconder SQL antes de entender as consultas;
- microserviços.
