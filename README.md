# Backend Studies

Repositório pessoal de estudos sobre **Engenharia de Backend**.

O objetivo é construir uma base de conhecimento progressiva e independente de linguagem ou framework, reunindo conceitos, materiais, anotações, exercícios e pequenos experimentos sobre os principais temas de desenvolvimento backend.

> O foco deste repositório não é decorar ferramentas. É entender os fundamentos, os problemas que cada tecnologia resolve e os trade-offs envolvidos nas decisões de engenharia.

## Como usar este repositório

Cada tópico possui seu próprio diretório com:

- explicação sobre por que o assunto é importante;
- conceitos que devem ser estudados;
- materiais recomendados;
- exercícios e problemas práticos;
- espaço para futuras anotações e exemplos.

A sugestão é avançar na ordem do roadmap, mas revisitar os assuntos sempre que eles aparecerem em problemas reais.

## Roadmap de Backend

### Nível 1 — Fundamentos

- [ ] [01. Fundamentos da Web e HTTP](./01-fundamentos-web/)
- [ ] [02. APIs e Contratos de Comunicação](./02-apis/)
- [ ] [03. Banco de Dados e Modelagem](./03-banco-de-dados/)
- [ ] [04. Transações e Consistência](./04-transacoes-consistencia/)
- [ ] [08. Autenticação e Autorização](./08-autenticacao-autorizacao/)
- [ ] [09. Segurança de Aplicações](./09-seguranca/)

### Nível 2 — Engenharia de Software

- [ ] [05. Arquitetura de Software](./05-arquitetura-software/)
- [ ] [06. Princípios de Design de Software](./06-design-software/)
- [ ] [07. Domain-Driven Design — DDD](./07-ddd/)
- [ ] [10. Testes de Software](./10-testes/)

### Nível 3 — Backend Avançado

- [ ] [11. Concorrência e Processamento Assíncrono](./11-concorrencia-assincronismo/)
- [ ] [12. Mensageria e Arquitetura Orientada a Eventos](./12-mensageria-eventos/)
- [ ] [13. Sistemas Distribuídos](./13-sistemas-distribuidos/)
- [ ] [14. Cache](./14-cache/)

### Nível 4 — Engenharia de Sistemas

- [ ] [15. Performance e Escalabilidade](./15-performance-escalabilidade/)
- [ ] [16. Observabilidade](./16-observabilidade/)
- [ ] [17. Containers e Infraestrutura](./17-containers-infraestrutura/)
- [ ] [18. CI/CD e Entrega de Software](./18-ci-cd/)
- [ ] [19. Cloud](./19-cloud/)
- [ ] [20. System Design](./20-system-design/)

## Por que essa ordem?

Os primeiros tópicos constroem o entendimento do funcionamento de uma aplicação backend: comunicação, contratos e dados. Em seguida entram arquitetura, design e testes, que ajudam a manter sistemas maiores. Depois aparecem concorrência, cache, mensageria e sistemas distribuídos, onde as falhas e a consistência ficam mais complexas. Por fim, performance, observabilidade, infraestrutura, cloud e system design conectam desenvolvimento ao comportamento real de sistemas em produção.

## Método de estudo sugerido

Para cada assunto:

1. Entender o problema que o conceito resolve.
2. Estudar os fundamentos antes de uma ferramenta específica.
3. Construir um exemplo pequeno.
4. Analisar um cenário real de falha ou trade-off.
5. Registrar as próprias conclusões no diretório do tópico.
6. Criar um exercício ou projeto pequeno para validar o entendimento.

## Estrutura

```text
backend-studies/
├── README.md
├── 01-fundamentos-web/
├── 02-apis/
├── 03-banco-de-dados/
├── 04-transacoes-consistencia/
├── 05-arquitetura-software/
├── 06-design-software/
├── 07-ddd/
├── 08-autenticacao-autorizacao/
├── 09-seguranca/
├── 10-testes/
├── 11-concorrencia-assincronismo/
├── 12-mensageria-eventos/
├── 13-sistemas-distribuidos/
├── 14-cache/
├── 15-performance-escalabilidade/
├── 16-observabilidade/
├── 17-containers-infraestrutura/
├── 18-ci-cd/
├── 19-cloud/
└── 20-system-design/
```

## Evolução do repositório

Este repositório deve crescer junto com os estudos. Os diretórios podem receber futuramente:

```text
README.md
anotacoes.md
exemplos/
exercicios/
referencias.md
```

Não é necessário preencher tudo de uma vez. A proposta é transformar o repositório em uma base de conhecimento construída ao longo do tempo.
