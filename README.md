
<div align="center">

# joyce.data

### De dado bruto a decisão: pipelines e sistemas de IA que resolvem problemas reais

**Engenharia de Dados & IA** · SQL Server · ETL/ELT · Python · Power BI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joycequoos/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:joycequoos@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfólio-181717?style=flat&logo=googlechrome&logoColor=white)](https://joycequoos.github.io/)

</div>

---

## Sobre

Especialista em dados com raízes em QA — o que significa que, para mim, uma solução só está pronta quando é testada, validada e documentada.

Minha jornada começou em 2005, no suporte técnico, onde aprendi a ouvir o usuário e resolver problemas na raiz. A passagem por QA moldou minha visão analítica e crítica, e desde 2020 aplico essa bagagem como Especialista em Dados, atuando em ETL/ELT, SQL, Python e Power BI. Também tenho experiência com SSIS, .NET Framework e Azure, e venho me dedicando ao estudo de Big Data com Databricks e de IA aplicada a PLD/AML (Prevenção à Lavagem de Dinheiro).

Gosto de documentar minha trilha de aprendizado publicamente — este perfil reflete isso: cada repositório é uma etapa do caminho, não só um resultado final.

**Veja o portfólio completo, com cases de solução:** **[joycequoos.github.io →](https://joycequoos.github.io/)**

---

## Stack por domínio

**Engenharia de Dados**
`SQL Server` `ETL / SSIS` `Stored Procedures` `Python / Pandas / NumPy`

**IA & Automação**
`Claude AI` `Gemini` `.NET` `Prompt engineering aplicado`

**BI & Análise**
`Power BI` `Matplotlib / Seaborn` `Jupyter` `Storytelling de dados`

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat&logo=azuredevops&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)

---

## Problemas reais, soluções entregues

Três recortes do case de PLD (Prevenção à Lavagem de Dinheiro) — do pipeline de ingestão à priorização dos alertas. [Ver o storytelling completo →](https://joycequoos.github.io/storytelling_pld_1.html)

### 01 · ETL — Pipeline D-1 de ingestão para PLD
**Problema:** dados de clientes e operações chegam diariamente em arquivo bruto e precisam estar limpos e disponíveis antes das regras de Compliance rodarem.
**Solução:** pacote SSIS com 4 etapas — limpeza da staging, leitura/validação do arquivo D-1, execução de procedure de consolidação e liberação das tabelas para análise.
`D-1` ciclo de atualização · `4` etapas do pipeline

### 02 · REG — Motor de regras de detecção de transações suspeitas
**Problema:** verificar manualmente cada movimentação contra o limiar de Compliance não escala com o volume diário de operações.
**Solução:** regra automatizada que sinaliza transações acima do parâmetro definido e segrega os resultados em tabela própria, criando fila de trabalho para o time de Compliance.
`95` alertas gerados no dia · `5` produtos monitorados

### 03 · SQL — Priorização de alertas com SQL + Python
**Problema:** com dezenas de alertas gerados por dia, o Compliance precisa saber por onde começar a investigação.
**Solução:** conexão Python↔SQL Server (pymssql) para consultar alertas, ranquear os clientes com maior incidência e cruzar volume de movimentação com risco por produto.
`15` clientes priorizados · `Corretora` produto de maior risco relativo

---

## Áreas de estudo & projetos

| Área | Descrição |
|---|---|
| [Dados](https://github.com/joycequoos/Principal_Data/blob/main/README.md) | Trilha de Análise de Dados, Engenharia de Dados e Ciência de Dados / IA. |
| [Desenvolvimento](https://github.com/joycequoos/Development) | Python, Node.js, .NET, Full Stack e boas práticas de versionamento. |
| [Sites & Desenvolvimento Web](https://github.com/joycequoos/Sites/blob/main/README.md) | HTML, CSS, JavaScript e Bootstrap. |
| [Testes de Software / QA](https://github.com/joycequoos/Test_QA) | Estudos e práticas de automação de testes. |

---

## Vamos conversar?

Colaborações e novas conexões em Engenharia de Dados e IA.

- 🔗 Portfólio: [joycequoos.github.io](https://joycequoos.github.io/)
- 💼 LinkedIn: [linkedin.com/in/joycequoos](https://www.linkedin.com/in/joycequoos/)
- ✉️ E-mail: [joycequoos@gmail.com](mailto:joycequoos@gmail.com)

<div align="center">

✦ *joyce.data — pipelines e IA para problemas reais*

</div>
