# Laboratório PostgreSQL

Docker é apenas ferramenta operacional neste momento. O estudo aprofundado de containers acontece no módulo 17.

## Subir
Na pasta deste laboratório: `docker compose up -d`.

## Verificar
- `docker compose ps`
- `docker compose logs postgres`

## Acesso
- Host: `localhost`
- Porta: `5432`
- Database: `backend_studies`
- Usuário: `backend`
- Senha: `backend`

Essas credenciais são exclusivamente locais e educacionais.

## Terminal
Se tiver `psql` instalado: `psql -h localhost -p 5432 -U backend -d backend_studies`.

Também é possível usar DBeaver, pgAdmin ou outra ferramenta gráfica.

## Parar
`docker compose down`.

## Remover também os dados locais
`docker compose down -v`.

## Organização
Use schemas separados quando um experimento precisar isolar tabelas. Não use isso como desculpa para ignorar boa modelagem.
