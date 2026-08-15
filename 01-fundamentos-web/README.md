# 01 — Fundamentos da Web e HTTP

## Objetivo

Construir o modelo mental necessário para entender como clientes e servidores se comunicam antes de escrever uma API.

## Por que este módulo vem primeiro?

Sem entender request, response, DNS, HTTP e a relação cliente-servidor, frameworks de API viram uma coleção de comandos decorados. Este módulo é propositalmente mais teórico.

## Pré-requisitos

Nenhum conhecimento de backend ou Python é necessário.

## Conteúdo

- internet e modelo cliente-servidor;
- endereço IP, portas e noções de TCP;
- DNS;
- HTTP e HTTPS;
- request e response;
- métodos HTTP;
- status codes;
- headers;
- URI/URL;
- cookies e estado;
- cache HTTP em nível introdutório;
- stateless;
- visão geral do caminho cliente → rede → servidor → resposta.

## Tipo de prática

**Revisão e observação.** Não há implementação do e-commerce neste módulo.

É permitido observar requisições no navegador/DevTools, mas não é necessário criar uma API ou escrever código.

## Evolução do e-commerce

Nenhuma. O primeiro código será criado no módulo 02.

## Critério de conclusão

Você deve conseguir explicar, sem depender de framework:

1. o que acontece quando um cliente faz uma requisição HTTP;
2. a diferença entre request e response;
3. o papel de DNS, IP e porta;
4. o significado das principais famílias de status HTTP;
5. por que HTTP é considerado stateless.

Depois, responda [`exercicios.md`](./exercicios.md) e use [`materiais.md`](./materiais.md) para aprofundar.
