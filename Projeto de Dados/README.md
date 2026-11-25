# PROJETO DE CIÊNCIAS DE DADOS , MODELO CRISP-DM

## Entendimento do negócio

Analisar as solicitações e gastos anuais do almoxarifado do FNDE. Qual período possui mais solicitações de itens para o almoxarifado? Quais itens custam mais e são mais consumidos por setor?

## Entendimento dos dados

Os dados são de uma planilha do Excel com 15 colunas e 1964 linhas. A fonte da planilha é o portal de solicitação de serviços do almoxarifado do FNDE.

<img width="1062" height="996" alt="image" src="https://github.com/user-attachments/assets/e7fb5482-8b94-4968-90a8-2ca86bf76891" />

<img width="1907" height="422" alt="image" src="https://github.com/user-attachments/assets/c4d0f657-20e7-45b4-ab34-29d93450392f" />

## Preparação dos dados

Através do recurso do Power Query, colunas desnecessárias foram romvidas e os tipos dos dados padronizados.

## Modelagem

Para a construção do dashboard algumas variaveis foram criadas através de fórmulas DAX.

## Avaliação

O Dashboard é um recurso para consultas sobre solicitações realizadas para o almoxarifado do FNDE. Ele mostra que em 2024 o FNDE teve um gasto maior com a compra de itens do que em 2025,
além disso o maior custo de 2024 foi a compra de Headsets, enquanto que em 2025 o maior gasto foi com a aquisição de WebCams.
