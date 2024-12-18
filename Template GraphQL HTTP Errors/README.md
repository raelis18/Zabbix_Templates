# Zabbix Template GraphQL
## Descrição

Template para coleta de Metricas do GraphQL

## Versões testadas
Zabbix Versão 7 ou superior<br>

## Configuração

1. Realizar a importação do template no Zabbix 
2. Preencher as macros necessarias

## Macros utilizadas

1. {$TOKEN} - Token para acesso a API do GraphQL.
2. {$URL} - Endereço API Metrics do Graphql. Ex : https://api.graphql/metrics/graphql.

## Itens do tipo Script

1. Raw HTTP 400 Errors
2. Raw HTTP 500 Errors

## Itens dependentes

HTTP 4xx Errors<br>
HTTP 400 Errors<br>
HTTP 403 Errors<br>
HTTP 404 Errors<br>

HTTP 5xx Errors<br>
HTTP 500 Errors<br>
HTTP 502 Errors<br>
HTTP 503 Errors<br>




