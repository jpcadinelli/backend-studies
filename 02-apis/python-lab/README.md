# Python Lab — Primeira API

Python não é o objeto de estudo deste módulo. Este guia contém somente o necessário para executar o exercício.

## Preparação
1. Instale Python 3 atual.
2. Na pasta do projeto, crie ambiente virtual: `python -m venv .venv`.
3. Ative o ambiente virtual.
4. Instale FastAPI e um servidor ASGI, por exemplo: `pip install fastapi uvicorn`.

## Conceitos mínimos de Python usados
- módulos e imports;
- funções com `def`;
- listas e dicionários;
- type hints simples;
- funções `async` podem aparecer no framework, mas não precisam ser aprofundadas agora.

## O que o framework representa
Uma declaração de rota liga um método + caminho HTTP a uma função Python. A função recebe os dados da request e produz o valor que será serializado na response.

## Execução
Use a forma indicada pela documentação atual do FastAPI/Uvicorn para iniciar a aplicação em modo de desenvolvimento.

Referência: [FastAPI — First Steps](https://fastapi.tiangolo.com/tutorial/first-steps/).

## Regra
Não copie uma arquitetura pronta. O objetivo é primeiro sentir as limitações de uma aplicação simples.
