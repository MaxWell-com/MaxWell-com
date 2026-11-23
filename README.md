# Hi, I'm MaxWell 👋

### Data Scientist · AI Engineer · LLM agents

I build **LLM agents that business people can trust with numbers**: they understand questions in natural language, call the right analytical tools, and code checks every figure before the user sees it. I come from data science (production forecasting and analytics), so I treat an agent like any other model: it ships with a test suite, an evaluation set and honest metrics.

**What I work on**

- 🤖 **Agent design.** Tool-calling agents where *code owns the numbers and the model owns the narrative*: deterministic NLU before the LLM, argument override, fact-only summaries, and verification of every number, unit and sign in the answer.
- 🧪 **LLM evaluation.** Eval sets built from real user questions and reference answers, with strict automated checks: right tool, right arguments, every number. Plus fast tests that need no LLM, so every change can be checked in CI.
- 🔒 **Local and private LLMs.** Open models (Qwen via Ollama) running on-premise. Only aggregated facts reach the model, never raw data. The agents are model-agnostic and scale from a laptop to a GPU server.
- 📈 **Machine learning in production.** Demand forecasting with gradient-boosting ensembles, leakage-safe backtesting, out-of-time evaluation.
- 🛠️ **AI-assisted engineering.** I build and refactor with coding agents (Claude Code), using planning, sub-agents and test-first workflows.

## Featured projects

| Project | What it is |
|---|---|
| 🤖 [**retail-sales-ai-analyst**](https://github.com/MaxWell-com/retail-sales-ai-analyst) | LLM agent that answers Russian-language business questions over ~24M rows of retail sell-out data. 13 analytical tools including LMDI factor analysis, distribution, pricing, assortment and forecasting. Russian NLU with morphology, number verification layer, 362 tests without an LLM, 39-question strict eval. FastAPI · DuckDB · Ollama |
| 📈 [**sku-demand-forecasting**](https://github.com/MaxWell-com/sku-demand-forecasting) | Monthly demand forecast for 600 SKUs: nowcasting, LightGBM/CatBoost ensemble, leakage-safe rolling-origin backtest. Out-of-time WAPE 24.9% vs 31.9% for the best baseline |
| 📊 [**sales-performance-dashboard**](https://github.com/MaxWell-com/sales-performance-dashboard) | One-page sales cockpit for a manufacturer: sales vs prior year, plan vs actual, unfulfilled demand, stock cover, auto-generated executive summary, rule-based client agent, 16-dimension associative filtering over an in-memory snapshot. Node.js · Express · OLAP (DAX/XMLA) |
| 🚚 [**service-level-dashboard**](https://github.com/MaxWell-com/service-level-dashboard) | How much of what customers ordered did they get: sales vs. unshipped orders by week, partner, brand and SKU, plus four deterministic, explainable recommendation rules (costly, chronic and never-shipped deficit, under-served partners). Live DAX queries with cache invalidation by cube refresh. Node.js · Express · OLAP (DAX/XMLA) |

All production projects are published on synthetic data that reproduces the statistical properties and data defects of the original. The code, methods and tests are the real ones.

## Stack

**LLM & agents:** tool calling · Ollama · Qwen · prompt design · eval harnesses · output verification · Claude Code
**ML & data:** Python · pandas · NumPy · LightGBM · CatBoost · Optuna · statsmodels · SQL · DuckDB · DAX / SSAS
**Engineering & BI:** FastAPI · Node.js / Express · Docker · pytest · GitHub Actions · vanilla JS dashboards

## Study projects

| Project | Topic |
|---|---|
| [ecommerce-rfm-segmentation](https://github.com/MaxWell-com/ecommerce-rfm-segmentation) | Customer RFM segmentation, DAU/MAU, statistical hypothesis testing |
| [credit-scoring-risk-analysis](https://github.com/MaxWell-com/credit-scoring-risk-analysis) | Bank borrower credit-risk analysis |
| [food-delivery-orders-eda](https://github.com/MaxWell-com/food-delivery-orders-eda) | Food-delivery orders exploratory data analysis |

---

**RU:** Data Scientist и AI-инженер. Проектирую LLM-агентов, которым бизнес может доверить цифры. Агент понимает вопрос на естественном языке и вызывает аналитические инструменты, а каждое число в ответе проверяет код. Строю eval-наборы и тесты для агентов, работаю с локальными LLM (Ollama, Qwen) без передачи данных наружу. Опыт production-ML: прогноз спроса на градиентном бустинге с честной валидацией.
