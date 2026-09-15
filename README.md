## SangHun Lee

Backend engineer. Python, FastAPI, Kubernetes.


### What I'm working on

- ML pipeline for commercial real estate price estimation. LightGBM, CatBoost and XGBoost ensemble at 15.3% MAPE, MLflow tracking on EKS, 300+ experiments. Promotion is decided by paired Wilcoxon and bootstrap CI, not a single split.
- An internal Slack assistant built on Claude API and MCP. Code analysis, natural language DB queries and Jira drafting, all in one channel.
- Retrieval for that assistant. bge-m3 embedding kNN routes intent and the LLM only breaks ties. I tested retrieval on about 100 real questions before adopting it, found grep-based agent search worked better for answering, and moved retrieval to routing instead of answer generation.
- Gold labels collected from real usage logs, used to calibrate routing confidence thresholds. Only validated examples get into the production index.
- One MCP server unifying Jira, Slack, Notion and Datadog tools, with a hand-written Markdown/ADF converter.
- FastAPI services on EKS with Helm, currently at 99.9% availability.

### Open source

- [cmux](https://github.com/manaflow-ai/cmux) (macOS terminal, Swift): made `setup.sh` fail early on a missing Metal or Rust toolchain instead of dying mid-build, and fixed the prerequisites it never documented. [#12352](https://github.com/manaflow-ai/cmux/pull/12352)
- Reported a native-fullscreen window bug there with a 4 Hz `CGWindowList` probe, turning "the screen looks broken" into exact frame coordinates and ruling out the pane layout. [#11822](https://github.com/manaflow-ai/cmux/issues/11822)

### Before that

- Normalized tables with hundreds of millions of rows and tuned the queries. Reads got about 18x faster.
- Archived 900M rows of member statistics, cutting table storage by 90%.
- Moved EKS nodes to ARM Graviton and cut cost by 20%.

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)

![Claude](https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-3B6E8F?style=for-the-badge&logo=optuna&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white)

### Links

- nrhys2005@gmail.com
- [Blog](https://hunstory.tistory.com/)
- [AWS Certified Solutions Architect – Associate](https://www.credly.com/badges/b9b9ff21-9d3f-45f2-a98a-50917e9b9b8f/public_url)
