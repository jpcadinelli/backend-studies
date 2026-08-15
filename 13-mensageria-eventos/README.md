# 13 — Mensageria e Eventos

## Objetivo
Desacoplar trabalho que não precisa terminar dentro do request.

## Conteúdo
broker, queue, topic, producer, consumer, command x event, delivery semantics, retries e DLQ.

## Evolução
Após criar um pedido, publicar `OrderCreated` e processar uma notificação simulada em consumidor separado.
