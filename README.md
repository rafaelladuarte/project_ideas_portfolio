# Ideias de Projetos de Portfólio - Engenharia de Dados

Este repositório contém uma coleção de ideias para projetos de portfólio na área de Engenharia de Dados. Cada projeto foi pensado para desenvolver e demonstrar habilidades em Big Data, arquitetura de dados, pipelines de ETL, ingestão de dados em tempo real, governança e machine learning.

## 🎯 Objetivo

O objetivo deste repositório é organizar e documentar ideias de projetos que podem ser desenvolvidos futuramente para fortalecer meu portfólio em Engenharia de Dados. As descrições incluem o propósito de cada projeto, as ferramentas que poderiam ser usadas e o valor que cada um deles agregaria.

## 📁 Estrutura das Ideias de Projetos

Cada ideia está documentada com uma breve descrição, as ferramentas e tecnologias recomendadas, além do objetivo específico de aprendizado e demonstração de habilidades.

## ⚙️ Projetos em Desenvolvimento

### 1. **Pipeline de ETL com Apache Airflow**
   - **Status**: Em desenvolvimento
   - **Repositório**: [GitHub - real_state_data_pipeline](https://github.com/rafaelladuarte/real_state_data_pipeline)
   - **Descrição**: Este projeto terá como objetivo desenvolver um pipeline de dados automatizado com Apache Airflow, que coletará, transformará, armazenará e visualizará dados do mercado imobiliário. A extração será feita por meio de web scraping com Selenium, seguida de limpeza e cálculo de métricas como preço médio por bairro. Os dados tratados serão armazenados em bancos como PostgreSQL ou MongoDB e visualizados em dashboards interativos para facilitar a análise de tendências.
   - **Ferramentas**: Docker, Apache Airflow, Python (Selenium), PostgreSQL, MongoDB
   - **Objetivo**: Automatizar e escalar o processamento de dados por meio do Apache Airflow, garantindo controle de dependências, agendamento de tarefas e modularidade no pipeline de ETL.

## 💡 Ideias de Projetos

### 1. **Construção de um Data Lake e Data Warehouse em Nuvem**
   - **Descrição**: Criar uma arquitetura que combine um Data Lake e um Data Warehouse para armazenar dados estruturados e não estruturados, otimizando o acesso aos dados.
   - **Ferramentas**: AWS (S3, Glue, Redshift), Azure Data Lake, Google BigQuery.
   - **Objetivo**: Demonstrar processos de ingestão de grandes volumes de dados, ETL e consultas rápidas para análise.

### 2. **AvesRAG – Sistema de Classificação Baseado em Grafo e LLM**
   - **Descrição**: Criação de um sistema inteligente para classificação de aves com base em um grafo de conhecimento estruturado, relacionando informações de taxonomia, morfologia, alimentação, habitat e distribuição. O grafo será usado em conjunto com um modelo de linguagem (LLM), que interpretará descrições fornecidas por usuários e sugerirá as espécies mais prováveis, utilizando RAG (Retrieval-Augmented Generation).
   - **Ferramentas**: Neo4j, Python, OpenAI GPT com LangChain ou LlamaIndex, FastAPI ou Streamlit
   - **Objetivos**: Construir um grafo de conhecimento com dados ricos sobre aves, Relacionar características observáveis com espécies reais, Permitir que um usuário descreva uma ave e receba sugestões prováveis de espécies, Usar RAG com LLM para classificação contextual baseada no grafo
   - **Base de dados**: GBIF(Taxonomia e distribuição geográfica), eBird OU Birds of the World (Nome comum, nome científico, habitat, alimentação). TraitBank (Morfologia (bico, cauda, asas, etc.) e hábitos), Avibase (Subespécies e classificações)

### 3. **Ingestão de Dados em Tempo Real com Kafka e Spark Streaming**
   - **Descrição**: Configurar um sistema de processamento em tempo real com Apache Kafka para ingestão de eventos de alta frequência e Spark Streaming.
   - **Ferramentas**: Apache Kafka, Apache Spark Streaming, HDFS, ElasticSearch.
   - **Objetivo**: Criar um pipeline de streaming para análise e visualização de dados em tempo real.

### 4. **Arquitetura Lambda para Processamento de Big Data**
   - **Descrição**: Desenvolver uma arquitetura Lambda combinando processamento em lote e em tempo real.
   - **Ferramentas**: Apache Hadoop, Apache Kafka, Spark, HDFS, AWS Lambda.
   - **Objetivo**: Implementar uma arquitetura robusta para dados históricos e eventos em tempo real.

### 5. **Processamento de Grandes Volumes de Dados com Apache Hadoop**
   - **Descrição**: Construir um pipeline de processamento de dados distribuídos em clusters HDFS.
   - **Ferramentas**: Apache Hadoop, HDFS, MapReduce, Hive.
   - **Objetivo**: Demonstrar habilidades de processamento distribuído para grandes volumes de dados.

### 6. **Data Governance e Qualidade de Dados em um Data Lake**
   - **Descrição**: Projetar uma arquitetura de Data Lake com práticas de governança, controle de qualidade, catalogação e versionamento.
   - **Ferramentas**: AWS Glue, Apache Atlas, AWS S3, Databricks.
   - **Objetivo**: Assegurar qualidade e governança de dados em um ambiente escalável.

### 7.  **Construção de uma Arquitetura de Dados em Nuvem para Análise em Tempo Próximo ao Real**
   - **Descrição**: Desenvolver uma solução de arquitetura de dados para monitorar ônibus da SPTrans em São Paulo, utilizando dados da API "Olho Vivo" e GTFS. O projeto incluiu a ingestão, processamento e visualização de dados em tempo próximo ao real, com foco em métricas como geolocalização, previsão de chegada e percentual de circulação.
   - **Ferramentas**: Airflow (orquestração), Spark (processamento), MinIO (armazenamento), Metabase (visualização), Presto (consultas SQL), Docker (conteinerização).
   - **Objetivo**: Demonstrar a construção de um pipeline de dados escalável, desde a coleta de dados brutos até a criação de dashboards interativos, com foco em análise de dados de transporte público.
   - **Referência**: [Festival de Verão 2025 LabData FIA - Case SPTrans](https://www.youtube.com/watch?v=cLL5gppwwqA&list=PLkaqDF7JQGzLGWL6_0ZqYlEIgAqQJag5Q&index=16)

### 8. **Monitoramento de Pipelines de Dados em Big Data**
   - **Descrição**: Desenvolver um sistema de monitoramento e alerta para pipelines de Big Data.
   - **Ferramentas**: Apache Airflow, Prometheus, Grafana.
   - **Objetivo**: Monitorar e garantir a saúde de pipelines em grande escala.

### 9. **Sistema de Denúncias em Tempo Real para Investigações Criminais**
   - **Descrição**: Criar um sistema integrado com WhatsApp, permitindo o envio de denúncias diretamente para autoridades policiais.
   - **Ferramentas**: Twilio API, Python, Elasticsearch, MongoDB, Kibana/Grafana.
   - **Objetivo**: Facilitar o envio de denúncias em tempo real, centralizando o armazenamento e visualização para otimizar investigações.
   - **Referência**: [Hackathon: Tecnologias Disruptivas para Segurança Pública](https://www.gov.br/mj/pt-br/assuntos/sua-seguranca/seguranca-publica/hackathon-tecnologias-disruptivas-para-seguranca-publica)7
      - [Apresentações das Equipes Vencedoras](https://www.gov.br/mj/pt-br/assuntos/sua-seguranca/seguranca-publica/confira-as-apresentacoes-das-equipes)

### 10. **OpenSky CDC DataLake**
   - **Repositório**: [OpenSky CDC DataLake](https://github.com/rafaelladuarte/opensky-cdc-datalake)
   - **Descrição**: Captura e replicação de dados de tráfego aéreo em tempo real, utilizando Change Data Capture (CDC) para armazenar e analisar dados de voos da OpenSky Network.
   - **Ferramentas**: PostgreSQL, Debezium, Apache Kafka, Python, mIMO (Data Lake), Docker, Trino/Iceberg.
   - **Objetivo**: Demonstrar o uso de CDC para ingestão de dados contínuos, garantindo armazenamento eficiente e permitindo análises avançadas.
   - **Referência**: [FIA Festival CDC Data Lake](https://github.com/Labdata-FIA/fia-vestival-cdc-lake)


## 📄 Licença

Este repositório está disponível sob a licença MIT. Sinta-se à vontade para explorar, contribuir com ideias ou se inspirar para seus próprios projetos!
