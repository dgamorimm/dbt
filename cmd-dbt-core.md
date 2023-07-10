## Instalação - Python >= 3.7
- pip install dbt-core
- pip install dbt-postgres
- dbt --version

## Iniciando o projeto
- dbt init `nome-do-projeto`

## Configurar a conexão
- cd ~/.dbt/
- nano  profiles.yml

## Verifica se esta tudo bem com o projeto
- cd `nome-do-projeto`
- dbt debug

## Criando o source
- cd models
- nano source.yml

## Criando o modelo
- Employees
  - veja se já esta na pasta models
  - nano employees.sql
  - executando o modelo
    - dbt run --select employees.sql