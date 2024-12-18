# Zabbix Template GraphQL
## Descrição

Template para coleta da quantidade de erros HTTP utilizando o GraphQL

## Versões testadas
Zabbix Versão 7 ou superior<br>

## Configuração

1. Realizar a importação do template no Zabbix 
2. Preencher as macros necessarias

## Macros utilizadas

1. {$TOKEN} - Token para acesso a API do GraphQL.
2. {$URL} - Endereço API Metrics do Graphql. Ex : https://api.graphql/metrics/graphql.
3. {$HTTP_4xx_LIMIT} - Quantidade de erros HTTP 4xx para gerar alarmes.
4. {$HTTP_400_LIMIT} - Quantidade de erros HTTP 400 para gerar alarmes.
5. {$HTTP_403_LIMIT} - Quantidade de erros HTTP 403 para gerar alarmes.
6. {$HTTP_404_LIMIT} - Quantidade de erros HTTP 404 para gerar alarmes.
7. {$HTTP_5XX_LIMIT} - Quantidade de erros HTTP 5xx para gerar alarmes.
8. {$HTTP_500_LIMIT} - Quantidade de erros HTTP 500 para gerar alarmes.
9. {$HTTP_502_LIMIT} - Quantidade de erros HTTP 502 para gerar alarmes.
10. {$HTTP_503_LIMIT} - Quantidade de erros HTTP 503 para gerar alarmes.



## Itens do tipo Script

Raw HTTP 400 Errors

Raw HTTP 500 Errors

## Itens dependentes

HTTP 4xx Errors

HTTP 400 Errors

HTTP 403 Errors

HTTP 404 Errors

HTTP 5xx Errors

HTTP 500 Errors

HTTP 502 Errors

HTTP 503 Errors

## Triggers

Quantidade de erros HTTP 4xx maior que {$HTTP_4xx_LIMIT}

Quantidade de erros HTTP 5xx maior que {$HTTP_5xx_LIMIT}

Quantidade de erros HTTP 400 maior que {$HTTP_400_LIMIT}

Quantidade de erros HTTP 403 maior que {$HTTP_403_LIMIT}

Quantidade de erros HTTP 404 maior que {$HTTP_404_LIMIT}

Quantidade de erros HTTP 500 maior que {$HTTP_500_LIMIT}

Quantidade de erros HTTP 502 maior que {$HTTP_502_LIMIT}

Quantidade de erros HTTP 503 maior que {$HTTP_503_LIMIT}




