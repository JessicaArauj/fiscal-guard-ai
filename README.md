<span align="justify">

## Overview

Fiscal Guard AI ingests official federal datasets Portal da Transparencia, Tesouro Nacional, CGU Orçamento Publico to answer key oversight questions:

- Who are the top expenses per federal program each year?
- Are there abnormal growth patterns in any expense category?
- Which payments deviate strongly from the historical behavior?
- How do commitment, accrual, and payment compare across the budget?

## Project Scope

- Government level: **Brazilian Federal Government**.
- MVP outputs: Warehouse, star schema, anomaly detection pipeline, LLM-based summaries and Dashboards.

### Primary Data Sources

- **Portal da Transparencia REST API**  
  Swagger: `https://api.portaldatransparencia.gov.br/`

- **Tesouro Nacional Transparente – Custos API**  
  Dataset: `https://www.tesourotransparente.gov.br/consultas/custos-api-de-dados-abertos`

- **CGU - Orçamento Público**  
  Dataset: `https://dados.gov.br/dados/conjuntos-dados/orcamento-publico`

## Prerequisites

- Python 3.11+
- API key for Portal da Transparência: `PORTAL_API_KEY`

## Open Source and Community

This repository is released under the [MIT License](LICENSE), which allows reuse in commercial and government contexts provided attribution is preserved. Contributions from the community are welcome review [CONTRIBUTING.md](CONTRIBUTING.md) for the workflow and reference the [Code of Conduct](Code%20of%20Conduct.md) when engaging with other contributors.

</span>
