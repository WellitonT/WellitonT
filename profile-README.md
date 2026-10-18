# Olá, sou o Welliton 👋

Desenvolvedor autodidata no Rio de Janeiro, em transição de carreira para tecnologia. Meu foco é **Dados e Machine Learning**: construo a base em engenharia de dados e infraestrutura para chegar a **MLOps e AI Engineering**.

*English: self-taught developer building data engineering and infrastructure foundations (Python, SQL, ETL, testing, Linux) on the path to ML and MLOps.*

## Projeto principal

**[NBA Data Warehouse](https://github.com/WellitonT/nba-data-warehouse)** é um pipeline ETL em Python que puxa estatísticas da API oficial da NBA, trata a qualidade dos dados e carrega tudo em um warehouse SQLite com tabelas dimensão e fato.

- **Extração resiliente:** retry com backoff e logging estruturado, porque a API da NBA é instável.
- **Qualidade de dados:** remove as linhas de totalização (`TOT`) de jogadores trocados de time, que duplicariam qualquer soma, e corrige tipos numéricos.
- **Carga idempotente:** constraint `UNIQUE` + `INSERT OR IGNORE`, então rodar o pipeline duas vezes não duplica dados.
- **Testes:** `pytest` com mock da API (sem depender de rede) e banco de teste isolado.
- **Próximo passo:** dashboard analítico para visualizar os dados do warehouse.

Também mantenho o **[TechStore Analytics](https://github.com/WellitonT/techstore-analytics)**, projeto onde consolidei POO aplicada, testes automatizados e arquitetura de software, e o **[network-security-lab](https://github.com/WellitonT/network-security-lab)**, onde pratico Linux, SSH e automação de infraestrutura.

## Stack

**Uso na prática:** Python (POO, tratamento de erros, `pathlib`) · SQL e SQLite · pandas · APIs REST (`requests`, `nba_api`) · pytest e mock · Git e GitHub · Linux e shell

**Estudando agora:** Linux, redes e terminal (fase atual) · depois containers, CI/CD, cloud, Machine Learning e MLOps

## Trilha

`Python e POO ✔` → `Python para dados ✔` → `Linux, redes e Git (em andamento)` → `Containers, CI/CD e Cloud` → `Machine Learning e MLOps` → `AI Engineering`

Todo estudo é aplicado em projetos contínuos, não em exercícios isolados. Os commits dos repositórios são o registro do que realmente fiz.

## Contato

- LinkedIn: [welliton-tiene-336bb7207](https://www.linkedin.com/in/welliton-tiene-336bb7207/)
