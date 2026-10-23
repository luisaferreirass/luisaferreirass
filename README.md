## Luisa Ferreira

**Engenheira de Dados Júnior** · Ciência da Computação @ UFRN<br>
Construo pipelines de dados: da ingestão via APIs à camada analítica.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/luisaferreirass)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:luisaferreirass08@gmail.com)

---

### Sobre mim

- Foco em **Engenharia de Dados**: ingestão, modelagem, orquestração e qualidade de dados
- Estudando agora: **Airflow**, **SQL avançado** e modelagem dimensional (star schema, SCD2)
- Português (nativo) · Inglês (avançado) · Francês (intermediário)

### Stack

**Linguagens & Ingestão**<br>
<img src="https://skillicons.dev/icons?i=py,fastapi,graphql&perline=10" height="40"/>

**Orquestração & Processamento**<br>
<img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white"/>
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Parquet-50ABF1?style=for-the-badge&logo=apacheparquet&logoColor=white"/>

**Bancos de dados**<br>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,sqlite" height="40"/>

**BI, Infra & Versionamento**<br>
<img src="https://skillicons.dev/icons?i=grafana,docker,git,github,gitlab" height="40"/>

### Projeto em destaque: Spotify Analytics Pipeline

```mermaid
flowchart LR
    A[Spotify API] --> B[Coletores Python]
    B --> C[(PostgreSQL)]
    C --> D[Views SQL]
    D --> E[FastAPI]
    E --> F[Dashboard]
    G{{Airflow}} -.orquestra.-> B
```

[Ver repositório →](https://github.com/luisaferreirass/spotify_analytics_pipeline)

### Outros projetos

| Projeto | O que faz | Stack |
|---|---|---|
| **[flight_search_app](https://github.com/luisaferreirass/flight_search_app)** | Ingestão automatizada da API Amadeus com persistência em banco | Python, API REST, SQL |
| **[data_clean](https://github.com/luisaferreirass/data_clean)** | Limpeza e tratamento de dados: ausentes, duplicatas, winsorização | Python, Pandas |
| **[HomeMatch](https://github.com/DevlTz/HomeMatch)** | Plataforma imobiliária com busca semântica (pgvector) e dados do Censo IBGE 2022 | Django, PostgreSQL, Celery, Redis |
