# Backend Studies

Roadmap sequencial de estudos de **Engenharia de Backend**, independente de linguagem na teoria e baseado em um único projeto prático evolutivo: um **e-commerce simplificado**.

A proposta não é estudar ferramentas isoladas. Cada módulo apresenta um problema ou conceito de backend no momento em que ele passa a fazer sentido. Quando houver exercício com código, a implementação evolui o mesmo projeto existente.

## Princípios do repositório

1. **Teoria primeiro.** Nenhum exercício exige um conceito que ainda não apareceu no roadmap.
2. **Um único projeto cumulativo.** Todo exercício de implementação evolui `project/ecommerce`.
3. **Python é ferramenta, não matéria.** A teoria é geral; os `python-lab` explicam apenas o Python necessário para aplicar o conteúdo.
4. **PostgreSQL é a implementação relacional de referência.** Bancos não relacionais são apresentados conceitualmente e entram na prática quando houver necessidade real, como Redis em cache.
5. **Docker é usado cedo como ferramenta operacional e estudado profundamente depois.** No módulo de banco ele apenas ajuda a subir PostgreSQL; o estudo de containers acontece no módulo 17.
6. **Materiais são curados por relevância.** Documentação oficial, artigos, papers, vídeos e livros podem ser antigos ou recentes; o critério principal é a qualidade e a utilidade para o assunto.
7. **Nem todo módulo precisa de código.** Revisão, observação, análise e modelagem também são exercícios válidos.

## Projeto evolutivo

O laboratório central é um e-commerce simplificado. O escopo pode incluir, quando o conteúdo justificar:

- produtos;
- clientes;
- carrinho;
- pedidos e itens;
- estoque;
- pagamento simulado;
- autenticação e autorização;
- cache;
- eventos e processamento assíncrono;
- observabilidade;
- automação de entrega.

Funcionalidades só entram quando ajudam a ensinar um conceito. O objetivo não é reproduzir um e-commerce comercial completo.

Veja: [`project/ecommerce/README.md`](./project/ecommerce/README.md).

## Roadmap

### Fundamentos e primeira aplicação
- [ ] [01. Fundamentos da Web e HTTP](./01-fundamentos-web/)
- [ ] [02. APIs e Contratos](./02-apis/)
- [ ] [03. Banco de Dados e Modelagem](./03-banco-de-dados/)
- [ ] [04. Transações e Consistência](./04-transacoes-consistencia/)

### Qualidade e engenharia de software
- [ ] [05. Testes de Software](./05-testes/)
- [ ] [06. Arquitetura de Software](./06-arquitetura-software/)
- [ ] [07. Design de Software](./07-design-software/)
- [ ] [08. Domain-Driven Design](./08-ddd/)

### Identidade, proteção e backend avançado
- [ ] [09. Autenticação e Autorização](./09-autenticacao-autorizacao/)
- [ ] [10. Segurança](./10-seguranca/)
- [ ] [11. Concorrência e Assincronismo](./11-concorrencia-assincronismo/)
- [ ] [12. Cache](./12-cache/)
- [ ] [13. Mensageria e Eventos](./13-mensageria-eventos/)
- [ ] [14. Sistemas Distribuídos](./14-sistemas-distribuidos/)

### Produção e consolidação
- [ ] [15. Observabilidade](./15-observabilidade/)
- [ ] [16. Performance e Escalabilidade](./16-performance-escalabilidade/)
- [ ] [17. Containers e Infraestrutura](./17-containers-infraestrutura/)
- [ ] [18. CI/CD](./18-ci-cd/)
- [ ] [19. Cloud](./19-cloud/)
- [ ] [20. System Design](./20-system-design/)

## Estrutura de cada módulo

Quando aplicável:

```text
XX-topico/
├── README.md       # objetivo, teoria, pré-requisitos e papel no projeto
├── materiais.md    # artigos, papers, documentação, vídeos e livros
├── exercicios.md   # revisão, observação ou implementação cumulativa
└── python-lab/     # somente quando Python precisa ser explicado para a prática
```

Alguns módulos também possuem arquivos de ambiente específicos. Eles só aparecem quando passam a ser necessários.

## Como estudar

Para cada módulo:

1. Leia o `README.md`.
2. Estude os materiais principais de `materiais.md`.
3. Responda os exercícios conceituais sem consultar a resposta imediatamente.
4. Se houver implementação, siga o enunciado e os guias locais.
5. Registre decisões e dificuldades no `STUDY-LOG.md`.
6. Só avance quando conseguir explicar **por que** a solução funciona e quais trade-offs ela possui.

A progressão desejada é:

```text
Conhecer → Entender → Observar → Experimentar → Implementar → Diagnosticar → Projetar
```
