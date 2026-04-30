Projeto: Análise de Dados – Estados com Maior Consumo e Custo de Energia
Data: 19/01/2026

Este relatório descreve o desenvolvimento de um projeto de análise de dados em nuvem, utilizando serviços da Amazon Web Services (AWS). O projeto tem como objetivo armazenar, processar e visualizar dados, permitindo identificar padrões e indicadores relevantes, como os estados com maior consumo.

FASE DO PROJETO 

A implementação do projeto foi dividida em três etapas, cada uma utilizando um serviço específico da AWS.

Etapa 1 – Armazenamento de Dados (Amazon S3)
Finalidade: Armazenamento de dados

Nesta etapa, os dados brutos do projeto foram armazenados no Amazon S3, utilizando arquivos no formato CSV. Esses dados representam informações organizadas por estado, permitindo análises posteriores.

O S3 foi escolhido por oferecer alta disponibilidade, durabilidade e facilidade de acesso, sendo ideal como camada inicial de um pipeline de dados.

Etapa 2 – Processamento e Preparação de Dados (AWS Glue
Finalidade: Processamento, catalogação e transformação de dados

O AWS Glue foi utilizado para preparar os dados armazenados no S3, realizando tarefas como:

Organização das colunas
Padronização dos registros
Estruturação dos dados para análise

Essa etapa é fundamental para garantir qualidade, consistência e confiabilidade das informações utilizadas nas análises.

Etapa 3 – Análise e Visualização de Dados (Amazon QuickSight)
Finalidade: Análise e visualização de dados

Na etapa final, o Amazon QuickSight foi utilizado para criar dashboards interativos, permitindo:

Comparar dados entre estados
Identificar os maiores consumos e custos
Visualizar rankings e gráficos analíticos

O fluxo do projeto segue a arquitetura abaixo:

Dados (CSV)
   ↓
Amazon S3
   ↓
AWS Glue (ETL)
   ↓
Amazon QuickSight (Dashboards)

O projeto demonstra, na prática, como a computação em nuvem pode ser utilizada para análise de dados e apoio à tomada de decisões.

Responsável pelo Projeto:

Michelle Maria
