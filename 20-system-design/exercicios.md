# Exercício Final — System Design

Projete três cenários:
1. pequeno: centenas de usuários;
2. médio: dezenas de milhares;
3. grande: milhões de usuários.

Para cada cenário, responda:
- quais são os requisitos funcionais e não funcionais?;
- onde estão os gargalos?;
- como banco, cache e mensageria evoluem?;
- qual consistência cada fluxo exige?;
- o que acontece se Redis, broker ou banco falharem?;
- o monólito ainda serve? Se não, qual limite justificaria separação?;
- quais sinais de observabilidade sustentariam decisões?;
- quais trade-offs você aceita?

O objetivo é justificar, não desenhar a arquitetura mais complexa possível.
