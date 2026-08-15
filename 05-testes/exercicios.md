# Exercícios — Testes

## Implementação
Crie testes que protejam o comportamento existente antes da próxima refatoração:
- criação/listagem de produto;
- produto inexistente;
- criação de pedido;
- estoque insuficiente;
- rollback quando uma etapa da criação do pedido falha;
- integração real com PostgreSQL para pelo menos os fluxos críticos.

## Reflexão
Para cada teste, classifique se ele protege uma regra de negócio, integração ou detalhe de implementação. Remova testes sem valor claro.
