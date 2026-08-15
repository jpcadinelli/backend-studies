# 04 — Transações e Consistência

## Objetivo
Entender como preservar invariantes quando várias alterações precisam ocorrer como uma unidade.

## Conteúdo
- ACID;
- BEGIN, COMMIT e ROLLBACK;
- isolation levels;
- locks;
- dirty/non-repeatable/phantom reads em nível conceitual;
- atomicidade e invariantes;
- deadlocks em nível introdutório.

## Evolução do e-commerce
Introduzir pedido, itens e estoque. Criar pedido deve persistir dados e reduzir estoque de forma consistente.

## Problema central
O que acontece se o pedido for salvo, mas a atualização de estoque falhar?
