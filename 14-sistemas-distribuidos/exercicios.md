# Exercícios — Sistemas Distribuídos
Analise e trate cenários:
1. banco salva pedido, publicação do evento falha;
2. consumer recebe o mesmo evento duas vezes;
3. broker fica temporariamente indisponível;
4. operação externa excede timeout.

Implemente pelo menos idempotência no consumidor e uma estratégia coerente para consistência entre banco e evento. Explique quando usar outbox.
