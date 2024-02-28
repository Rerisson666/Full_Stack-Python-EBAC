# Full_Stack-Python-EBAC

## Criar conta no Github

## Clonar o projeto

## Commits
Informação de alteração
- Após testar todo seu código
- git add *
- git commit -m "mensagem"
- git push (enviar alterações para o repositório)
- git pull (puxar / trazer alterações do Git para sua máquina)

## GitFlow
Fluxo do Git

### Branchs
São ramificações / versões paralelas

- main / master (vai pra produção, quando o projeto é publicado)
- develop
- DOD Definition of Done: critérios de aceite
- versionamento 1.0.0

git checkout -b dev (cria uma branch)
git checkout master (cria uma branch)

### Merge
Mescla de branchs
Você pode precisar resolver conflios manualmente

git merge main

### Pull Requests
Mesclar de branchs no repositório
Permite code review
O respositório resolve os conflitos automaticamente

### configura o GitFlow
git flow init
git flow feature start {nome-da-feature}
