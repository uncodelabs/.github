# Politica de Seguranca

## Reportando Vulnerabilidades

Se voce descobrir uma vulnerabilidade de seguranca em qualquer repositorio da Uncode, por favor **nao abra uma issue publica**.

Entre em contato diretamente com o time pelo Teams ou pelo email de contato da empresa. Responderemos o mais rapido possivel.

## Boas Praticas

Todos os repositorios da Uncode seguem estas regras:

- Nunca fazer commit de secrets, credenciais ou chaves de API
- Nunca fazer commit de arquivos `.env`, `*.pem` ou `credentials.json`
- Nunca fazer `push --force` em `main` ou `master`
- RLS (Row Level Security) obrigatorio em todos os projetos com Supabase
- Validacao de input com Zod em todas as boundaries do sistema
