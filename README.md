# Relat-rioAWSDIO.DADOS
RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 19/01/2026
Empresa: Energia
Responsável: Michelle Maria

Introdução

Este relatório apresenta o processo de implementação de serviços em nuvem na empresa Energia, realizado por Michelle Maria. O objetivo do projeto foi selecionar e aplicar três serviços da Amazon Web Services (AWS) com a finalidade de armazenar, processar e visualizar dados relacionados ao consumo e custo de energia elétrica, destacando os estados com os maiores índices de consumo e valores mais elevados.

A adoção da computação em nuvem visa melhorar a organização dos dados, facilitar análises estratégicas e apoiar a tomada de decisões baseada em informações confiáveis e atualizadas.

Descrição do Projeto

O projeto de implementação foi dividido em três etapas, cada uma utilizando um serviço AWS específico, conforme descrito a seguir.

Etapa 1 – Amazon S3 (Simple Storage Service)

Nome da ferramenta: Amazon S3

Foco da ferramenta: Armazenamento de dados

Descrição do caso de uso:

O Amazon S3 foi utilizado para armazenar os dados brutos de consumo e custo de energia elétrica, organizados por estado e período (mês/ano). Os arquivos, no formato CSV, contêm informações como estado, consumo médio (kWh) e valor médio da tarifa.

Esse serviço garante alta durabilidade, segurança e fácil acesso aos dados, servindo como base para as etapas seguintes do projeto.

Etapa 2 – AWS Glue

Nome da ferramenta: AWS Glue

Foco da ferramenta: Processamento e preparação de dados (ETL)

Descrição do caso de uso:

O AWS Glue foi utilizado para catalogar, limpar e transformar os dados armazenados no Amazon S3. Nesta etapa, foram realizadas tarefas como:

Padronização dos nomes dos estados

Remoção de dados inconsistentes

Organização das informações para análise

O Glue permitiu automatizar o processo de tratamento dos dados, garantindo qualidade e confiabilidade das informações antes da análise final.

Etapa 3 – Amazon QuickSight

Nome da ferramenta: Amazon QuickSight

Foco da ferramenta: Análise e visualização de dados

Descrição do caso de uso:

O Amazon QuickSight foi utilizado para criar dashboards interativos, permitindo a visualização clara dos estados com os maiores custos e maiores consumos de energia elétrica.

Foram gerados gráficos comparativos, rankings por estado e análises visuais que facilitam a identificação de padrões, apoiando gestores na tomada de decisões estratégicas, como planejamento energético e controle de custos.

Conclusão

A implementação dos serviços Amazon S3, AWS Glue e Amazon QuickSight na empresa Energia proporciona diversos benefícios, como:

Melhor organização e segurança dos dados

Automação no processamento das informações

Facilidade na análise e visualização dos dados energéticos

Apoio à tomada de decisões estratégicas

Com isso, espera-se um aumento da eficiência operacional e da produtividade, além de maior confiabilidade nas análises realizadas. Recomenda-se a continuidade do uso das ferramentas implementadas e a busca por novas soluções tecnológicas que possam aprimorar ainda mais os processos da empresa.

Anexos

Planilhas de dados de consumo de energia (CSV)

Prints dos dashboards do Amazon QuickSight

Documentação básica dos serviços AWS utilizados

Assinatura do Responsável pelo Projeto:
Michelle Maria
