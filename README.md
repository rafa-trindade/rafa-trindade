```python
@dataclass
class AboutMe:
  
    name: str = "Rafael Araujo Trindade"
    
    profession: str = "Data & Analytics Professional"
    
    preferred_tech_stack: List[str] = field(
        default_factory=lambda: [
            "Python", "PySpark", "SQL", "DBT", 
            "DuckDB", "ETL/ELT", "Apache Airflow",
            "Terraform", "Docker", "Kubernetes"
        ]
    )
    
    applied_in: List[str] = field(
        default_factory=lambda: [
            "Analytics Engineering",
            "Data Engineering",
            "Workflow Automation"
        ]
    )
```

<div align="justify">
  
  <b>Engenheiro de Dados & Analytics</b> com experiência na construção de arquiteturas eficientes, governáveis e escaláveis, com foco em performance, rastreabilidade e uso inteligente de recursos.
  Atuação no desenvolvimento de soluções resilientes por meio de <b>engenharia orientada a dados</b>, priorizando impacto e clareza técnica acima de ferramentas específicas.
  Foco na construção de pipelines e arquiteturas analíticas que garantem confiabilidade, rastreabilidade e suporte consistente à tomada de decisão.
  Aberto a projetos de alto impacto, com foco em engenharia bem feita, escala e geração de valor sustentável.

</div>

<div align="center">𝗗𝗔𝗧𝗔-𝗗𝗥𝗜𝗩𝗘𝗡 𝗘𝗡𝗚𝗜𝗡𝗘𝗘𝗥𝗜𝗡𝗚, 𝗡𝗢𝗧 𝗧𝗢𝗢𝗟-𝗗𝗥𝗜𝗩𝗘𝗡</div>

</br>

<div align="center">

![Analytics Engineering](https://img.shields.io/badge/-Analytics%20Engineering-2B5482?style=flat)
![Data Engineering](https://img.shields.io/badge/-Data%20Engineering-2B5482?style=flat)
![Data Modeling](https://img.shields.io/badge/-Data%20Modeling-2B5482?style=flat)
![Data Quality](https://img.shields.io/badge/-Data%20Quality-2B5482?style=flat)
![Data Governance](https://img.shields.io/badge/-Data%20Governance-2B5482?style=flat)
![Observability](https://img.shields.io/badge/-Observability-2B5482?style=flat)
![Process Optimization](https://img.shields.io/badge/-Process%20Optimization-2B5482?style=flat)

</div>

<div align="center">

[![Databricks Fundamentals](docs/badges/dtb-fundamentals.png)](https://credentials.databricks.com/1ddd8ad3-0432-4d6b-a280-251f3b7e929a)&nbsp;
[![Airflow Fundamentals](docs/badges/af-fundamentals.png)](https://www.credly.com/badges/e009d579-a996-4083-858f-efa7224a7659/linked_in_profile)&nbsp;
[![Airflow DAGs](docs/badges/af-dag.png)](https://www.credly.com/badges/a758b9c7-ce8f-4a03-bd88-6db21ed6f067/linked_in_profile)&nbsp;
[![FAD 4.0 BR](docs/badges/FAD-4-br.png)](https://drive.google.com/file/d/13XIyPdRbYIwV-2pG63NCZsumSTwamNKz/view)&nbsp;
[![FAE 4.0 BR](docs/badges/FAE-4-br.png)](https://drive.google.com/file/d/1QtBGcKScamFhxn0A4SCtYbjcLmU2CKkN/view)&nbsp;
[![FAE 3.0 BR](docs/badges/FAE-3-br.png)](https://drive.google.com/file/d/1ntb7OlUK8niom9TuPunf9xBcSg7fwCdh/view)

</div>

```python
@dataclass
class Project:
    name: str
    description: str
    technologies: List[str]

@dataclass
class Portfolio:
    projects: List[Project] = field(default_factory=list)

portfolio = Portfolio(
    projects=[
```

<div align="center">

[![Kaggle Dathub](https://github-readme-stats-rafatrindade.vercel.app/api/pin/?username=rafa-trindade&repo=kaggle-datahub&theme=github_dark_dimmed&show_owner=false&description_lines_count=4&bg_color=151B23&langs_count=3)](https://github.com/rafa-trindade/kaggle-datahub)
[![oncoped-data-br](https://github-readme-stats-rafatrindade.vercel.app/api/pin/?username=rafa-trindade&repo=oncoped-360&theme=github_dark_dimmed&show_owner=false&description_lines_count=4&bg_color=151B23&langs_count=10)](https://github.com/rafa-trindade/oncoped-360)
[![PetStore Pipeline](https://github-readme-stats-rafatrindade.vercel.app/api/pin/?username=rafa-trindade&repo=petstore-pipeline&theme=github_dark_dimmed&show_owner=false&description_lines_count=3&bg_color=151B23&langs_count=6)](https://github.com/rafa-trindade/petstore-pipeline)
[![pdp-analytics-engineering](https://github-readme-stats-rafatrindade.vercel.app/api/pin/?username=rafa-trindade&repo=pdp-analytics-engineering&theme=github_dark_dimmed&show_owner=false&description_lines_count=4&bg_color=151B23&langs_count=9)](https://github.com/rafa-trindade/pdp-analytics-engineering)
[![BI rafatrindade](https://github-readme-stats-rafatrindade.vercel.app/api/pin/?username=rafa-trindade&repo=bi-rafatrindade&theme=github_dark_dimmed&show_owner=false&description_lines_count=4&bg_color=151B23&langs_count=9)](https://github.com/rafa-trindade/bi-rafatrindade)
[![Dashboard Grupotamburi](https://github-readme-stats-rafatrindade.vercel.app/api/pin/?username=rafa-trindade&repo=b2b-grupotamburi&theme=github_dark_dimmed&show_owner=false&description_lines_count=4&bg_color=151B23&langs_count=9)](https://github.com/rafa-trindade/b2b-grupotamburi)
[![PetStore Scraping](https://github-readme-stats-rafatrindade.vercel.app/api/pin/?username=rafa-trindade&repo=petstore-scraping&theme=github_dark_dimmed&show_owner=false&description_lines_count=4&bg_color=151B23&langs_count=9)](https://github.com/rafa-trindade/petstore-scraping)
[![PetStore Transform Load](https://github-readme-stats-rafatrindade.vercel.app/api/pin/?username=rafa-trindade&repo=petstore-etl&theme=github_dark_dimmed&show_owner=false&description_lines_count=4&bg_color=151B23&langs_count=9)](https://github.com/rafa-trindade/petstore-etl)
[![PetStore BI](https://github-readme-stats-rafatrindade.vercel.app/api/pin/?username=rafa-trindade&repo=petstore-bi&theme=github_dark_dimmed&show_owner=false&description_lines_count=4&bg_color=151B23&langs_count=10&langs_count=9)](https://github.com/rafa-trindade/petstore-bi)
[![PDP Hospedagem](https://github-readme-stats-rafatrindade.vercel.app/api/pin/?username=rafa-trindade&repo=pdp-hospedagem&theme=github_dark_dimmed&show_owner=false&description_lines_count=4&bg_color=151B23&langs_count=9)](https://github.com/rafa-trindade/pdp-hospedagem)
[![Top Langs](https://github-readme-stats-rafatrindade.vercel.app/api/top-langs/?username=rafa-trindade&theme=github_dark_dimmed&bg_color=151B23&hide_title=true&card_width=804&langs_count=4&exclude_repo=controle-contas,web-embritania&size_weight=0.5&count_weight=0.5&hide_progress&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
<!--[![Data Faker](https://github-readme-stats-rafatrindade.vercel.app/api/pin/?username=rafa-trindade&repo=datafaker-rafatrindade&theme=github_dark_dimmed&show_owner=false&description_lines_count=2&bg_color=151B23&langs_count=10)](https://github.com/rafa-trindade/datafaker-rafatrindade)-->

</div>

```python
    ]
)
```

[![rafa-trindade github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=rafa-trindade&theme=react&hide_border=true&hide_title=false&radius=10&height=350&bg_color=151B23&line=2c5a95&point=2B5482)](https://github.com/rafa-trindade)
