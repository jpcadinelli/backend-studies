# Python Lab — PostgreSQL

Objetivo: mostrar apenas o necessário para Python conversar com PostgreSQL.

## Estude antes
Entenda SQL e o modelo relacional no README do módulo.

## Pontos necessários
- instalar um driver PostgreSQL compatível com Python;
- abrir conexão;
- executar comandos parametrizados;
- ler resultados;
- confirmar ou desfazer operações quando aplicável;
- liberar conexões adequadamente.

Uma opção comum é Psycopg. Consulte a documentação atual: [Psycopg](https://www.psycopg.org/psycopg3/docs/).

## Regra de segurança
Nunca monte SQL concatenando entrada do usuário. Use parâmetros oferecidos pelo driver.

## Escopo
Não aprofundar ORM neste momento. O objetivo é manter visível a relação entre API, SQL e banco.
