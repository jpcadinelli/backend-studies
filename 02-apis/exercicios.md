# Exercícios — APIs e Contratos

## Revisão
1. O que diferencia recurso, rota e endpoint?
2. Quando path param e query param são mais adequados?
3. Por que `POST /products` tende a retornar 201 em uma criação bem-sucedida?
4. Qual a diferença entre PUT e PATCH?
5. O que torna um contrato de API previsível?

## Implementação cumulativa
Crie a primeira versão de `project/ecommerce` seguindo o guia em `python-lab/README.md`.

### Requisitos
- `GET /products` — listar produtos;
- `GET /products/{id}` — obter produto;
- `POST /products` — criar produto;
- dados mantidos apenas em memória;
- validar campos obrigatórios;
- retornar status codes coerentes;
- documentar exemplos de request/response.

### Restrições pedagógicas
- não adicionar banco;
- não adicionar autenticação;
- não criar camadas arquiteturais complexas;
- priorizar um contrato simples e compreensível.

## Perguntas após implementar
1. O que acontece com os produtos quando a aplicação reinicia?
2. Qual problema isso cria?
3. Quais partes do código já começaram a misturar responsabilidades?
