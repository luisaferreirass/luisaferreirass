<!-- Header animado -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A66C2,100:00ADD4&height=140&section=header&text=Luisa%20Ferreira&fontSize=40&fontColor=ffffff&fontAlignY=38" width="100%" alt="header"/>

<div align="center">

<!-- Texto digitando -->
<a href="https://github.com/luisaferreirass">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=0A66C2&center=true&vCenter=true&width=620&lines=Engenheira+de+Dados+J%C3%BAnior;Pipelines+da+ingest%C3%A3o+%C3%A0+camada+anal%C3%ADtica;Lakehouse+%7C+Spark+%7C+Delta+%7C+Iceberg+%7C+Trino;Ci%C3%AAncia+da+Computa%C3%A7%C3%A3o+%40+UFRN" alt="Typing SVG"/>
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/luisaferreirass)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:luisaferreirass08@gmail.com)

</div>

---

### 🧰 Stack

<div align="center">

**Ingestão & Linguagens**<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Lakehouse & Processamento**<br/>
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square)
![Iceberg](https://img.shields.io/badge/Iceberg-2C7BB6?style=flat-square)
![Trino](https://img.shields.io/badge/Trino-DD00A1?style=flat-square&logo=trino&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Orquestração, Bancos & Infra**<br/>
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

### ⭐ Projetos em destaque

<table>
<tr>
<td width="50%" valign="top">

#### 🎧 Spotify Analytics Pipeline
Pipeline ponta a ponta: coleta via API do Spotify, persistência em PostgreSQL, views SQL analíticas, API em FastAPI e dashboard. Tudo orquestrado com Airflow.

`Python` `Airflow` `PostgreSQL` `FastAPI`

[![Repo](https://img.shields.io/badge/Ver%20reposit%C3%B3rio-181717?style=flat-square&logo=github)](https://github.com/luisaferreirass/spotify_analytics_pipeline)

</td>
<td width="50%" valign="top">

#### 🛒 Olist Lakehouse
Pipeline sobre o dataset público de e-commerce da Olist: transformações com Spark, tabelas em Delta Lake e consultas analíticas via Trino.

`Spark` `Delta Lake` `Trino`

[![Repo](https://img.shields.io/badge/Ver%20reposit%C3%B3rio-181717?style=flat-square&logo=github)](https://github.com/luisaferreirass/NOME_DO_REPO_OLIST)

</td>
</tr>
</table>

<details>
<summary><b>Ver arquitetura dos dois projetos</b></summary>

<br/>

**Spotify Analytics Pipeline**

```mermaid
flowchart LR
    A[Spotify API] --> B[Coletores Python]
    B --> C[(PostgreSQL)]
    C --> D[Views SQL]
    D --> E[FastAPI]
    E --> F[Dashboard]
    G{{Airflow}} -.orquestra.-> B
```

**Olist Lakehouse**

```mermaid
flowchart LR
    A[Dataset Olist] --> B[Spark]
    B --> C[(Delta Lake)]
    C --> D[Trino]
    D --> E[Consultas / BI]
```

</details>

---

<div align="center">

🗣️ Português (nativo) · Inglês (avançado) · Francês (intermediário)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ADD4,100:0A66C2&height=80&section=footer" width="100%" alt="footer"/>

</div>
