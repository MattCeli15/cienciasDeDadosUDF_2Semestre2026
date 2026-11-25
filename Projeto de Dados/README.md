# PROJETO DE CIÊNCIAS DE DADOS , MODELO CRISP-DM

## Entendimento do negócio

Analisar as solicitações e gastos anuais do almoxarifado do FNDE. Qual período possui mais solicitações de itens para o almoxarifado? Quais itens custam mais e são mais consumidos por setor?

## Entendimento dos dados

Os dados são de uma planilha do Excel com 15 colunas e 1964 linhas. A fonte da planilha é o portal de solicitação de serviços do almoxarifado do FNDE.

<img width="1062" height="996" alt="image" src="https://github.com/user-attachments/assets/e7fb5482-8b94-4968-90a8-2ca86bf76891" />

<img width="1907" height="422" alt="image" src="https://github.com/user-attachments/assets/c4d0f657-20e7-45b4-ab34-29d93450392f" />

## Preparação dos dados

Através do recurso do Power Query, colunas desnecessárias foram romvidas e os tipos dos dados padronizados.

<img width="1909" height="1009" alt="image" src="https://github.com/user-attachments/assets/898001cd-8168-4d87-858a-ccebdc00b276" />

## Modelagem

Para a construção do dashboard algumas variaveis foram criadas através de fórmulas DAX.

<img width="1401" height="170" alt="image" src="https://github.com/user-attachments/assets/ef63b728-c350-4263-b132-64a01dd92217" />

<img width="1517" height="32" alt="image" src="https://github.com/user-attachments/assets/4b4f3bd7-ec2e-4e76-a639-d85c381fac08" />

<img width="1516" height="34" alt="image" src="https://github.com/user-attachments/assets/c3c9dcf1-1116-4a3c-8b85-2506ddc4a1f9" />

<img width="1522" height="34" alt="image" src="https://github.com/user-attachments/assets/a2fd8cec-d4a9-494d-b426-d23ec717de2c" />

A tabela de "Calendário" foi criada para filtrar os gráficos através das datas (meses, trimestres, anos)

<img width="1520" height="99" alt="image" src="https://github.com/user-attachments/assets/e955e5c5-7cd2-4507-8e4d-7a6f26b3d751" />

## Avaliação

O Dashboard é um recurso para consultas sobre solicitações realizadas para o almoxarifado do FNDE. Ele mostra que em 2024 o FNDE teve um gasto maior com a compra de itens do que em 2025,
além disso o maior custo de 2024 foi a compra de Headsets, enquanto que em 2025 o maior gasto foi com a aquisição de WebCams.

<img width="1528" height="813" alt="image" src="https://github.com/user-attachments/assets/3c4667ac-56f6-4b82-ac62-a5d6cd033921" />

<img width="1522" height="816" alt="image" src="https://github.com/user-attachments/assets/b406dad8-ab03-4226-9e73-2c9c38b59cd3" />

<img width="1528" height="818" alt="image" src="https://github.com/user-attachments/assets/dca09bb8-f4b0-4031-a1f7-f0230399d138" />
