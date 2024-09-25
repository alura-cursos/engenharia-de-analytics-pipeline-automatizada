# Curso: Construindo um Pipeline de ETL na AWS para Engenharia de Analytics Júnior

## 📖 Storytelling

Você foi contratado(a) como Engenheiro(a) de Analytics Júnior para um treinamento na Zoop. Durante esse treinamento, o Head de Dados da empresa lhe forneceu uma amostra de três bases de dados para que você possa utilizar os serviços da AWS para analisá-los, gerando relatórios e dashboards.

Este curso irá focar na criação da camada Gold a partir dos dados já tratados na camada Silver. Vamos trabalhar na geração de três insights principais:

- **Top 10 produtos mais vendidos por região**
- **Top 10 produtos com menor estoque restante**
- **O impacto das avaliações nas vendas**

Utilizaremos o AWS Athena para explorar as tabelas da camada Silver por meio de consultas SQL, preparando-nos para criar a camada Gold.

## 🗂 Base de Dados

Os dados tratados da camada Silver estão organizados em três principais conjuntos:

- **Zoop**: Contendo informações sobre vendas, estoque e redes sociais.

## 🎯 Objetivo do Curso

O curso tem como objetivo guiá-lo na construção de um pipeline de ETL utilizando o AWS Glue, que irá transformar os dados tratados da camada Silver em dados especializados na camada Gold, armazenados no Amazon S3. Você também aprenderá a criar o banco de dados e as tabelas no AWS por meio do Data Catalog.

Após a criação da camada Gold, construiremos e monitoraremos o pipeline completo do projeto de engenharia, desde o tratamento dos dados na camada Silver até a criação dos dados especializados na camada Gold.

Além disso, você aprenderá a implementar um pipeline ETL por meio do AWS Glue Visual ETL, utilizando Jobs que vão automatizar o pipeline com o Step Functions. Com o Step Functions, montaremos um fluxo de trabalho sequencial que irá processar a camada Silver, criar os dados da camada Gold e enviar notificações por e-mail em caso de sucesso ou falha no processo.

## 👥 Público Alvo

- Profissionais interessados em aprender a implementar pipelines de ETL com AWS para a criação de dados especializados.
- Pessoas que desejam automatizar todas as etapas do pipeline de ETL utilizando os serviços da AWS.
- Aspirantes a Engenheiros de Analytics que buscam desenvolver as habilidades necessárias para se destacarem na carreira.

## 🛠 Pré-requisitos

Para aproveitar ao máximo este curso, é importante ter conhecimentos básicos em:

- **Python**, especialmente na biblioteca **PySpark**, para o processamento de grandes volumes de dados com DataFrames e SQL de forma eficiente em clusters.

## 🚀 Projeto

O projeto do curso envolverá a construção de um pipeline de ETL com a seguinte stack tecnológica:

### 🔧 Tech Stack

- **Armazenamento**: Amazon S3
- **ETL e Qualidade de Dados**: AWS Glue Crawler, AWS Glue Data Catalog, AWS Glue ETL Job (Visual Studio e Script Editor), AWS Glue Data Quality
- **Orquestração**: AWS Step Functions
- **Linguagens e Ferramentas**: Python, Apache Spark, Athena, SQL

## 📊 Estrutura do Curso

1. **Explorando a camada Silver com o AWS Athena**: Consultas SQL para entender os dados.
2. **Criando a camada Gold**: Pipeline ETL com AWS Glue para transformar os dados.
3. **Implementando a automação com Step Functions**: Construindo um pipeline automatizado para tratar os dados e notificar em caso de sucesso ou falha.
