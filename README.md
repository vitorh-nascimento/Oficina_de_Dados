# README - Oficina de Dados

## Ferramentas Utilizadas

- **Google Colab**: Utilizado para manipulação e análise inicial das bases de dados.
- **GitHub**: Armazenamento das bases e versão dos códigos criados.
- **Power BI/Tableau/Looker**: Ferramentas de visualização de dados utilizadas para criar dashboards e relatórios interativos.

## Bases de Dados

### Base de Colaboradores

- **Estrutura**:
  - Nome (texto)
  - Data de Nascimento (data)
  - Tipo de Contrato (PJ, CLT ou EST)
  - Admissão (data)
  - Demissão (data)
  - Idade (inteiro)
  - Salário (float)
- **Características**:
  - Dados limpos e prontos para análise.
  - Utilizados para aprender conceitos básicos de estatística e Python.

### Base de Clientes

- **Estrutura**:
  - Nome (texto)
  - Data de Nascimento (texto)
  - Idade (texto)
  - Último Gasto (texto)
- **Características**:
  - Inclui erros intencionais, como tipos de dados incorretos e campos vazios.
  - Serve como base para aprender processos de limpeza e padronização de dados.

### Base de Vendas

- **Estrutura**:
  - ID (inteiro)
  - ID Cliente (1 a 30)
  - ID Colaborador (1 a 100)
  - Data de Compra (data)
  - Valor da Compra (float)
  - Cidade da Compra (texto)
  - Estado da Compra (texto)
  - País da Compra (texto)
- **Características**:
  - Contém 300 registros simulados de vendas entre 2023 e 2024.
  - Base utilizada para aprender ETL, estatística e visualização.

## Cronograma e Tarefas

### 1º Dia: Básicos de Dados

- **Objetivos**:
  - Compreender conceitos estatísticos como média, moda, mediana, percentis e desvio padrão.
  - Aprender manipulações básicas com Pandas no Google Colab.
- **Tarefas**:
  1. Importar as bases de dados de Colaboradores, Clientes e Vendas.
  2. Unificar as bases em um único DataFrame.
  3. Realizar cálculos estatísticos.
  4. Criar visualizações simples, como gráficos de barras e colunas.

### 2º Dia: Engenharia de Dados

- **Objetivos**:
  - Entender os tipos de arquivos (Parquet, Avro, CSV) e variáveis (qualitativas e quantitativas).
  - Explorar arquiteturas (AWS, Google, Azure) e processos de ETL e ELT.
- **Tarefas**:
  1. Usar a base de Vendas para:
     - Identificar e corrigir tipos de dados incorretos.
     - Renomear colunas para padrões consistentes.
     - Tratar dados ausentes (remover ou substituir).
  2. Salvar a base limpa em formato Parquet.

### 3º Dia: Análise de Dados

- **Objetivos**:
  - Diferenciar bancos OLTP e OLAP.
  - Compreender modelagem relacional e dimensional.
  - Aprender tipos de análises (descritiva, diagnóstica, preditiva, prescritiva).
  - Trabalhar com ferramentas como Power BI e Tableau.
- **Tarefas**:
  1. Importar a base limpa para o Power BI.
  2. Realizar transformações no Power Query:
     - Renomear e reorganizar colunas.
     - Substituir valores e unificar tabelas.
  3. Criar relacionamentos entre as tabelas.
  4. Desenvolver gráficos e dashboards interativos.

### 4º Dia: Ciências de Dados

- **Objetivos**:
  - Explorar Machine Learning supervisionado (classificação, regressão) e não supervisionado (clusterização).
  - Introduzir Deep Learning e IA Generativa.
- **Tarefas**:
  1. Criar um projeto básico no Google Colab:
     - Aplicar regressão ou classificação na base de Vendas.
     - Dividir a base em treino e teste.
     - Avaliar o modelo com métricas simples.
  2. Propor um desafio para os participantes elaborarem seus próprios modelos.

## Observações Finais

- Este projeto é uma jornada prática e teórica pelo universo dos dados.
- As bases foram elaboradas com diferentes graus de dificuldade para atender a cada etapa do aprendizado.
- Utilize as ferramentas sugeridas para maximizar seu entendimento.
- Dúvidas e feedbacks podem ser compartilhados no repositório do projeto no GitHub.
