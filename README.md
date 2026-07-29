<div align="center">

<img src="banner.svg" alt="joyce.data — Engenharia de Dados & IA" width="100%"/>


</div>

---

### ✦ Sobre

Especialista em dados com raízes em QA — o que significa que, para mim, uma solução só está pronta quando é testada, validada e documentada.

Minha jornada começou em 2005, no suporte técnico, onde aprendi a ouvir o usuário e resolver problemas na raiz. A passagem por QA moldou minha visão analítica e crítica, e desde 2020 aplico essa bagagem como Especialista em Dados, atuando em ETL/ELT, SQL, Python e Power BI. Também tenho experiência com SSIS, .NET Framework e Azure, e venho me dedicando ao estudo de Big Data com Databricks e de IA aplicada a PLD/AML (Prevenção à Lavagem de Dinheiro).

Gosto de documentar minha trilha de aprendizado publicamente — este perfil reflete isso: cada repositório é uma etapa do caminho, não só um resultado final.

**→ Veja o portfólio completo, com cases de solução: [joycequoos.github.io](https://joycequoos.github.io/)**

---

### ✦ Stack por domínio

<table width="100%">
<tr>
<td align="center" valign="top" width="33%">

**Engenharia de Dados**

![SQL Server](https://img.shields.io/badge/SQL%20Server-7C6FF0?style=flat-square&logo=microsoftsqlserver&logoColor=white)<br/>
![ETL/SSIS](https://img.shields.io/badge/ETL%20%2F%20SSIS-7C6FF0?style=flat-square&logo=databricks&logoColor=white)<br/>
![Python](https://img.shields.io/badge/Python%20%2F%20Pandas%20%2F%20NumPy-7C6FF0?style=flat-square&logo=python&logoColor=white)

</td>
<td align="center" valign="top" width="33%">

**IA & Automação**

![Claude AI](https://img.shields.io/badge/Claude%20AI-22D3EE?style=flat-square&logo=anthropic&logoColor=0B0F19)<br/>
![Gemini](https://img.shields.io/badge/Gemini-22D3EE?style=flat-square&logo=googlegemini&logoColor=0B0F19)<br/>
![.NET](https://img.shields.io/badge/.NET-22D3EE?style=flat-square&logo=dotnet&logoColor=0B0F19)

</td>
<td align="center" valign="top" width="33%">

**BI & Análise**

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

### ✦ Problemas reais, soluções entregues

Três recortes do case de PLD (Prevenção à Lavagem de Dinheiro) — do pipeline de ingestão à priorização dos alertas.
**→ [Ver o storytelling completo](https://joycequoos.github.io/storytelling_pld_1.html)**

<br/>

<table width="100%">
<tr>
<td width="100%">

![01](https://img.shields.io/badge/01-ETL-7C6FF0?style=flat-square)
**Pipeline D-1 de ingestão para PLD**

> **Problema:** dados de clientes e operações chegam diariamente em arquivo bruto e precisam estar limpos e disponíveis antes das regras de Compliance rodarem.
> **Solução:** pacote SSIS com 4 etapas — limpeza da staging, leitura/validação do arquivo D-1, execução de procedure de consolidação e liberação das tabelas para análise.

![D-1](https://img.shields.io/badge/D--1-ciclo%20de%20atualização-0B0F19?style=flat-square&labelColor=7C6FF0) ![4 etapas](https://img.shields.io/badge/4-etapas%20do%20pipeline-0B0F19?style=flat-square&labelColor=7C6FF0)

</td>
</tr>
<tr>
<td width="100%">

![02](https://img.shields.io/badge/02-REG-22D3EE?style=flat-square)
**Motor de regras de detecção de transações suspeitas**

> **Problema:** verificar manualmente cada movimentação contra o limiar de Compliance não escala com o volume diário de operações.
> **Solução:** regra automatizada que sinaliza transações acima do parâmetro definido e segrega os resultados em tabela própria, criando fila de trabalho para o time de Compliance.

![95](https://img.shields.io/badge/95-alertas%20gerados%20no%20dia-0B0F19?style=flat-square&labelColor=22D3EE) ![5](https://img.shields.io/badge/5-produtos%20monitorados-0B0F19?style=flat-square&labelColor=22D3EE)

</td>
</tr>
<tr>
<td width="100%">

![03](https://img.shields.io/badge/03-SQL-4C4AE3?style=flat-square)
**Priorização de alertas com SQL + Python**

> **Problema:** com dezenas de alertas gerados por dia, o Compliance precisa saber por onde começar a investigação.
> **Solução:** conexão Python↔SQL Server (pymssql) para consultar alertas, ranquear os clientes com maior incidência e cruzar volume de movimentação com risco por produto.

![15](https://img.shields.io/badge/15-clientes%20priorizados-0B0F19?style=flat-square&labelColor=4C4AE3) ![Corretora](https://img.shields.io/badge/Corretora-produto%20de%20maior%20risco-0B0F19?style=flat-square&labelColor=4C4AE3)

</td>
</tr>
</table>

---

### ✦ Áreas de estudo & projetos

| Área | Descrição |
|---|---|
| [Dados](https://github.com/joycequoos/Principal_Data/blob/main/README.md) | Trilha de Análise de Dados, Engenharia de Dados e Ciência de Dados / IA. |
| [Desenvolvimento](https://github.com/joycequoos/Development) | Python, Node.js, .NET, Full Stack e boas práticas de versionamento. |
| [Sites & Desenvolvimento Web](https://github.com/joycequoos/Sites/blob/main/README.md) | HTML, CSS, JavaScript e Bootstrap. |
| [Testes de Software / QA](https://github.com/joycequoos/Test_QA) | Estudos e práticas de automação de testes. |

---

<div align="center">

### Vamos conversar?

Colaborações e novas conexões em Engenharia de Dados e IA.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0B0F19?style=for-the-badge&logo=linkedin&logoColor=7C6FF0)](https://www.linkedin.com/in/joycequoos/)<br/>
[![GitHub](https://img.shields.io/badge/GitHub-0B0F19?style=for-the-badge&logo=github&logoColor=22D3EE)](https://github.com/joycequoos)<br/>
[![Email](https://img.shields.io/badge/Email-0B0F19?style=for-the-badge&logo=gmail&logoColor=7C6FF0)](mailto:joycequoos@gmail.com)

<br/>

✦ *joyce.data — pipelines e IA para problemas reais*

</div>
