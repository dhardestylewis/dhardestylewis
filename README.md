### Hi there 👋

<!--
**dhardestylewis/dhardestylewis** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

I design and implement intelligent decision support systems to support computational science, disaster mitigation and response, and resiliency research projects.

- 🔭 I’m currently working on ... country-scale flood modelling from source data all the way to visualization
- 🌱 I’m currently learning ... [Plotly Dash](https://github.com/plotly/dash), [OSMnx](https://github.com/gboeing/osmnx)
- 👯 I’m looking to collaborate on ...  global scaling of elevation & flood data workflows, scalable equitable land-use models
- 💬 Ask me about ... [GDAL](https://github.com/OSGeo/gdal), [PostgreSQL](https://github.com/postgres/postgres), [Geopandas](https://github.com/geopandas/geopandas) & [RasterIO](https://github.com/mapbox/rasterio)
- 📫 How to reach me: ... send me an email! See [https://github.com/dhardestylewis] for ways to contact me!

-->

# Daniel Hardesty Lewis

**Staff ML Engineer — production training, inference, evaluation, reliability**

I build and operate interpretable machine learning systems and scalable geospatial infrastructure for high-stakes decision support. I specialize in leakage-safe evaluation, distributional robustness, and end-to-end delivery from source data to production web products.

Links: [dlewis.ai](https://dlewis.ai) · [LinkedIn](https://www.linkedin.com/in/dhardestylewis/) · [Email](mailto:danielhardestylewis@gmail.com) · [GitHub](https://github.com/dhardestylewis)

---

## What I ship

- **Properlytic** — consumer real-estate pricing and forecasting with uncertainty fan charts and expanding-window, leakage-safe evaluation.  
- **Summit Geospatial** — high-resolution elevation data products and delivery infrastructure for engineering and hazard workflows.  
- **PoliBOM** — tariff intelligence and compliance workflows for manufacturers (BOM parsing, retrieval, and policy scenario simulation).  
- **Texas Disaster Information System (TDIS)** — statewide disaster data platform and modeling workflows supporting inter-agency response and resiliency planning.

---

## Focus areas

- **Leakage-safe forecasting systems:** evaluation harnesses, reliability, and model governance for decisions under uncertainty  
- **Interpretable ML for decision support:** stable, regime-aware attribution and explainability for high-stakes settings  
- **Geospatial + time-series pipelines:** source data → modeling → APIs → web delivery  
- **Distributed and HPC workflows:** performance profiling, scalability, and explicit cost–performance tradeoffs

---

## Selected work

### Properlytic (Co-founder)
Consumer property pricing and forecasting platform with interactive uncertainty fan charts.
- Deployed an NYC semi-supervised VAE current-price model using tax and sales records to handle sparsity and noise; achieved **12% holdout error** (vs. **Zillow 8.4%** internal apples-to-apples).
- Shipped a Houston diffusion-based forecasting system with fan charts; achieved **~8% annualized compounding error** at best-performing horizons, delivered via production web UI.

### Summit Geospatial (Founder)
High-resolution elevation data and web delivery for engineering and hazard workflows.
- Engineered a statewide seamless Texas DEM mosaic, resampling **0.5 m** LiDAR sources to **1.2 m** via nearest-neighbor across **70+** elevation datasets.
- Built the web distribution platform end-to-end (pipeline, tiling, hosting, delivery UX) for planning and engineering use cases.

### PoliBOM (Co-founder)
AI tariff mitigation and trade compliance for manufacturers.
- Specified an agentic workflow and schema definitions for BOM parsing, retrieval, and tariff simulation using embeddings + search, API serving, and operational data stores.
- Directed development of a conversational AI interface to simplify trade workflows, retrieval, and proactive compliance alerts.

### Texas Disaster Information System (TDIS) and TACC (Senior Data Scientist & Technical Lead; Data Scientist & Research Engineer)
State-scale climate, flood, and terrain workflows, including support for the **$40M** TDIS program.
- Scaled climate and flood models on supercomputers, executing large distributed jobs while managing multi-million-dollar compute budgets and federal partnerships.
- Developed methods to produce high-resolution flood maps from National Water Model outputs for operational response workflows.
- Partnered with federal and state agencies on technical scoping, milestones, and delivery pathways.

---

## Research

**Columbia University — Financial Engineering (Research Assistant, Industry-sponsored)**  
Explainable and distributionally robust ML for forecasting and decision support.
- Built a multi-asset CVAE latent factor model with Skew-T mixture priors; achieved **85% R²** vs. commercial SaaS (**75%**) and Fama-French (**58%**) on backtested holdout.
- Developed tractable, regime-aware attribution methods to improve stability and interpretability for deep forecasting models.

**Columbia University — Electrical Engineering (Research Assistant)**  
- Math benchmarking and finetuning work related to GRPO-style optimization.

---

## Technical stack

**Languages:** Python, SQL, Bash, TypeScript, C++, Fortran, PL/pgSQL  
**Modeling:** PyTorch, TensorFlow, scikit-learn, transformers, variational inference, SHAP  
**LLM apps:** embeddings, RAG, LangChain/LangGraph, DSPy, FAISS  
**Data:** Pandas, Polars, PyArrow, Parquet, Postgres, PostGIS, Redis, Elasticsearch, Supabase  
**Infra:** Linux/Unix, Docker, Kubernetes, Ray, Spark, Dask, Airflow, CI/CD, observability  
**Geospatial:** GDAL, GeoPandas, Rasterio  
**Acceleration:** CUDA

---

## Selected Publications

- *Artificial Intelligence for Modeling Complex Systems: Taming the Complexity of Expert Models to Improve Decision Making*
- *An Intelligent Interface for Integrating Climate, Hydrology, Agriculture, and Socioeconomic Models*
- *A Semantic Model Catalog to Support Comparison and Reuse*

---

## Contact

- Website: https://dlewis.ai  
- Email: danielhardestylewis@gmail.com  
- GitHub: https://github.com/dhardestylewis  
- LinkedIn: https://www.linkedin.com/in/dhardestylewis/  
- Location: New York, NY

