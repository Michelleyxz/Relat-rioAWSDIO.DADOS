RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Projeto: Análise de Dados – Estados com Maior Consumo e Custo de Energia
Data: 19/01/2026
Responsável: Michelle Maria

Introdução

Este relatório descreve o desenvolvimento de um projeto de análise de dados em nuvem, utilizando serviços da Amazon Web Services (AWS). O projeto tem como objetivo armazenar, processar e visualizar dados, permitindo identificar padrões e indicadores relevantes, como os estados com maior consumo e maior custo de energia.

O projeto foi desenvolvido com foco educacional e demonstrativo, simulando um cenário real de uso de computação em nuvem, análise de dados e visualização de informações para apoio à tomada de decisão.

Objetivo do Projeto

Demonstrar o uso prático de serviços AWS

Centralizar dados em nuvem

Processar e organizar dados brutos

Criar visualizações claras e intuitivas

Aplicar conceitos de ETL e Business Intelligence

Descrição do Projeto

A implementação do projeto foi dividida em três etapas, cada uma utilizando um serviço específico da AWS.

Etapa 1 – Armazenamento de Dados (Amazon S3)

Ferramenta: Amazon S3

Finalidade: Armazenamento de dados

Nesta etapa, os dados brutos do projeto foram armazenados no Amazon S3, utilizando arquivos no formato CSV. Esses dados representam informações organizadas por estado, permitindo análises posteriores.

O S3 foi escolhido por oferecer alta disponibilidade, durabilidade e facilidade de acesso, sendo ideal como camada inicial de um pipeline de dados.

Etapa 2 – Processamento e Preparação de Dados (AWS Glue)

Ferramenta: AWS Glue

Finalidade: Processamento, catalogação e transformação de dados

O AWS Glue foi utilizado para preparar os dados armazenados no S3, realizando tarefas como:

Organização das colunas

Padronização dos registros

Estruturação dos dados para análise

Essa etapa é fundamental para garantir qualidade, consistência e confiabilidade das informações utilizadas nas análises.

Etapa 3 – Análise e Visualização de Dados (Amazon QuickSight)

Ferramenta: Amazon QuickSight

Finalidade: Análise e visualização de dados

Na etapa final, o Amazon QuickSight foi utilizado para criar dashboards interativos, permitindo:

Comparar dados entre estados

Identificar os maiores consumos e custos

Visualizar rankings e gráficos analíticos

Essa visualização facilita a interpretação dos dados e simula um ambiente real de Business Intelligence (BI).

Arquitetura do Projeto

O fluxo do projeto segue a arquitetura abaixo:

Dados (CSV)
   ↓
Amazon S3
   ↓
AWS Glue (ETL)
   ↓
Amazon QuickSight (Dashboards)

Resultados Obtidos

Com a implementação do projeto, foi possível:

Centralizar dados em nuvem

Automatizar a preparação das informações

Criar análises visuais claras

Simular um pipeline de dados completo usando AWS

O projeto demonstra, na prática, como a computação em nuvem pode ser utilizada para análise de dados e apoio à tomada de decisões.

Conclusão

O desenvolvimento deste projeto permitiu aplicar conceitos de Cloud Computing, ETL e Visualização de Dados, utilizando serviços amplamente adotados no mercado. A integração entre Amazon S3, AWS Glue e Amazon QuickSight mostrou-se eficiente para a construção de um pipeline de dados simples, porém funcional.

O projeto pode ser facilmente expandido com novas fontes de dados, atualizações automáticas ou integrações com APIs externas, tornando-se uma excelente base para projetos futuros e para composição de portfólio profissional.

Anexos

Dataset utilizado no projeto (CSV)

Prints dos dashboards criados

Notebook de análise exploratória

README.md do projeto

Responsável pelo Projeto:
Michelle Maria