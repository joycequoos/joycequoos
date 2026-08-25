<div align="center">

<img src="banner.svg" alt="joyce.data — Data Engineering & Applied AI" width="100%"/>


</div>

---

### ✦ About

Data Engineer with a background in QA and Business Analysis — which means I think about data quality and integrity as part of the design, not as a final checklist.

Today I build data pipelines and SQL rules that flag possible fraud for analyst review, and I help put together reports and dashboards for the business. I work mainly with SQL, Python, AWS, Databricks, and ELT/SSIS, along with APIs in .NET (C#) and code versioning in Azure DevOps. I'm also learning and applying AI to reduce false positives in transaction monitoring (AML).

My journey started in 2005 in technical support, where I learned to listen to users and solve problems at the root — and I spent years in QA and Business Analysis on critical financial systems before moving into Data in 2020. That path shaped how I work today: I enjoy building the technical solution just as much as sitting down with whoever lives the problem, whether a client or a teammate, to understand what actually needs solving.

While my deepest experience is in finance, I'm driven by curiosity about how data solves problems in other contexts — and I'm open to bringing this way of working to new industries.

I document my learning journey publicly — this profile reflects that: every repository is a step along the way, not just a final result.

**→ See the full portfolio, with solution case studies: [joycequoos.github.io](https://joycequoos.github.io/)**

---

### ✦ Stack by Domain

<table width="100%">
<tr>
<td align="center" valign="top" width="33%">

**Data Engineering**

![SQL Server](https://img.shields.io/badge/SQL%20Server-7C6FF0?style=flat-square&logo=microsoftsqlserver&logoColor=white)<br/>
![ETL/SSIS](https://img.shields.io/badge/ETL%20%2F%20SSIS-7C6FF0?style=flat-square&logo=databricks&logoColor=white)<br/>
![Python](https://img.shields.io/badge/Python%20%2F%20Pandas%20%2F%20NumPy-7C6FF0?style=flat-square&logo=python&logoColor=white)

</td>
<td align="center" valign="top" width="33%">

**IA & Automation*

![Claude AI](https://img.shields.io/badge/Claude%20AI-22D3EE?style=flat-square&logo=anthropic&logoColor=0B0F19)<br/>
![Gemini](https://img.shields.io/badge/Gemini-22D3EE?style=flat-square&logo=googlegemini&logoColor=0B0F19)<br/>
![.NET](https://img.shields.io/badge/.NET-22D3EE?style=flat-square&logo=dotnet&logoColor=0B0F19)

</td>
<td align="center" valign="top" width="33%">

**BI & Analytics**

![Power BI](https://img.shields.io/badge/Power%20BI-4C4AE3?style=flat-square&logo=powerbi&logoColor=white)<br/>
![Jupyter](https://img.shields.io/badge/Jupyter-4C4AE3?style=flat-square&logo=jupyter&logoColor=white)<br/>
![Storytelling](https://img.shields.io/badge/Storytelling%20de%20Dados-4C4AE3?style=flat-square&logo=googleanalytics&logoColor=white)

</td>
</tr>
</table>
<table align="center">
<tr>
<td align="center">

![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0B0F19?style=flat-square&logo=azuredevops&logoColor=22D3EE)

</td>
<td align="center">

![Docker](https://img.shields.io/badge/Docker-0B0F19?style=flat-square&logo=docker&logoColor=22D3EE)

</td>
<td align="center">

![Airflow](https://img.shields.io/badge/Apache%20Airflow-0B0F19?style=flat-square&logo=apacheairflow&logoColor=22D3EE)

</td>
<td align="center">

![Databricks](https://img.shields.io/badge/Databricks-0B0F19?style=flat-square&logo=databricks&logoColor=22D3EE)

</td>
</tr>
</table>

---

### ✦ Real Problems, Delivered Solutions

Three snapshots from the AML (Anti-Money Laundering) case — from the ingestion pipeline to alert prioritization.
**→ [See the full storytelling](https://joycequoos.github.io/storytelling_pld_1.html)**

<br/>

<table width="100%">
<tr>
<td width="100%">

![01](https://img.shields.io/badge/01-ETL-7C6FF0?style=flat-square)
**Pipeline de ingestão de Dados**

> **Problem:**ach client or data source presents a different access scenario — raw files, relational databases, cloud storage volumes — and the same ingestion technique isn't always the most efficient or feasible across all cases.

Solution: ETL and ELT pipelines adapted to each source:

- SSIS — package orchestration in SQL Server environments
- Python — custom, flexible ingestions
- Bulk Insert — high-volume loads with performance in mind
- View reads — direct extraction from the client's database
- AWS/Azure — direct reads from cloud storage volumes
- Airflow (DAGs) — orchestration and scheduling for data loading pipelines
- APIs — reading JSON files, direct integration via API


![8 técnicas](https://img.shields.io/badge/6-formas%20de%20implementação-0B0F19?style=flat-square&labelColor=7C6FF0) ![ETL & ELT](https://img.shields.io/badge/ETL%20%26%20ELT-diversas%20abordagens-0B0F19?style=flat-square&labelColor=7C6FF0)

</td>
</tr>
<tr>
<td width="100%">

![02](https://img.shields.io/badge/02-REG-22D3EE?style=flat-square)
**Suspicious Transaction Detection Rules Engine**

> **Problem:** manually checking every transaction against the Compliance threshold doesn't scale with daily operation volume.
> **Solution:** an automated rule that flags transactions above the defined parameter and segregates the results into a dedicated table, creating a work queue for the Compliance team.

![95](https://img.shields.io/badge/95-alertas%20gerados%20no%20dia-0B0F19?style=flat-square&labelColor=22D3EE) ![5](https://img.shields.io/badge/5-produtos%20monitorados-0B0F19?style=flat-square&labelColor=22D3EE)

</td>
</tr>
<tr>
<td width="100%">

![03](https://img.shields.io/badge/03-SQL-4C4AE3?style=flat-square)
**Alert Prioritization with SQL + Python**

> **Problem:** with dozens of alerts generated daily, Compliance needs to know where to start the investigation.
> **Solution:** a Python↔SQL Server connection (pymssql) to query alerts, rank clients with the highest incidence, and cross-reference transaction volume with product risk.

![15](https://img.shields.io/badge/15-clientes%20priorizados-0B0F19?style=flat-square&labelColor=4C4AE3) ![Corretora](https://img.shields.io/badge/Corretora-produto%20de%20maior%20risco-0B0F19?style=flat-square&labelColor=4C4AE3)

</td>
</tr>
</table>

---

### ✦ Learning & Projects

| Area | Description |
|---|---|
| [Data (Analysis, Engineering, Science/AI](https://github.com/joycequoos/Principal_Data/blob/main/README.md) | Data Analysis, Data Engineering, and Data Science / AI track. |
| [Web Development](https://github.com/joycequoos/Development) | .NET, Angular,  HTML, CSS, JavaScript and other Web Development content |
| [Software Testing / QA](https://github.com/joycequoos/Test_QA) | Studies and practices in test planning, execution, reporting, and automation. |

---
### Exclusive AML Content

Additional materials, available separately, AML: [Exclusive AML Content](https://github.com/joycequoos/PLD_Principal/blob/main/README.md)

---

<div align="center">

### Let's Talk?

Collaborations and new connections in Data Engineering and AI.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0B0F19?style=for-the-badge&logo=linkedin&logoColor=7C6FF0)](https://www.linkedin.com/in/joycequoos/)<br/>
[![GitHub](https://img.shields.io/badge/GitHub-0B0F19?style=for-the-badge&logo=github&logoColor=22D3EE)](https://github.com/joycequoos)<br/>
[![Email](https://img.shields.io/badge/Email-0B0F19?style=for-the-badge&logo=gmail&logoColor=7C6FF0)](mailto:joycequoos@gmail.com)


<br/>


✦ *joyce.data — pipelines e IA para problemas reais*

</div>
