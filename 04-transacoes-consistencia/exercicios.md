# Exercícios — Transações e Consistência

## Revisão
1. O que significa atomicidade?
2. Por que rollback é importante?
3. O que isolation tenta controlar?
4. Por que locks podem causar problemas além de resolvê-los?
5. O que seria uma inconsistência entre pedido e estoque?

## Implementação
- modelar `orders`, `order_items` e estoque;
- criar operação de pedido;
- garantir que pedido + itens + redução de estoque sejam atômicos;
- provocar uma falha no meio da operação e comprovar rollback;
- documentar a invariante protegida.
