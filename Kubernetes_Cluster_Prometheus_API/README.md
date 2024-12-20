# Zabbix Template Kubernetes Cluster by Prometheus API
## Descrição

Template para coleta de Metricas de Cluster Kubernetes, utilizando a API do Prometheus

## Versões testadas
Zabbix Versão 6 ou superior<br>

## Configuração

1. Realizar a importação do template no Zabbix 
2. Preencher as macros necessarias

## Macros utilizadas

1. {$CLUSTER_CPU_DISASTER} - value: '95'
2. {$CLUSTER_CPU_HIGH} - value: '90'
3. {$CLUSTER_FILESYSTEM_DISASTER} - value: '95'
4. {$CLUSTER_FILESYSTEM_HIGH} - value: '93'
5. {$CLUSTER_MEMORY_DISASTER} - value: '98'
6. {$CLUSTER_MEMORY_HIGH} - value: '95'
7. {$ENDPOINT_URL} - value: "url_prometheus"
8. {$NAMESPACE} - value: "namespace onde estão os recursos que deseja monnitorar" 
9. {$POD_CPU_DISASTER} - value: '2'
10. {$POD_CPU_HIGH} - value: '1'
11. {$POD_CPU_PERCENT_DISASTER} - value: '95'
12. {$POD_CPU_PERCENT_HIGH} - value: '90'
13. {$POD_CPU_WARNING} - value: '80'
14. {$POD_MEMORY_PERCENT_DISASTER} - value: '98'
15. {$POD_MEMORY_PERCENT_HIGH} - value: '95'


## Itens do tipo Script



## Itens dependentes



## Triggers






