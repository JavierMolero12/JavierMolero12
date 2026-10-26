# Javier Molero Moreno

**Analista de datos · Machine Learning · Desarrollo de software**

Trabajo donde se cruzan los datos, el código y el machine learning. En un proyecto de datos me interesa tanto la pregunta como el proceso: datos verificados, hipótesis escritas antes de mirar los resultados y un pipeline que cualquiera pueda volver a ejecutar. Cuando la respuesta está clara, construyo la herramienta que la pone a funcionar.

**Portfolio:** [javier-molero.vercel.app](https://javier-molero.vercel.app) · **LinkedIn:** [javier-molero-moreno](https://www.linkedin.com/in/javier-molero-moreno-65126a356/) · **Email:** javiermoleromoreno1@gmail.com

---

## Proyectos

### [Customer Churn Analysis](https://github.com/JavierMolero12/customer-churn-analysis) · Análisis de datos y machine learning

¿A qué clientes debería llamar primero el equipo de retención? Análisis del abandono de 7.043 clientes de una operadora (IBM Telco) con un pipeline reproducible.

- Un solo comando regenera todo: descarga verificada con SHA-256, base de datos SQLite en 4 tablas y tabla final de 7.043 clientes × 27 variables.
- 14 comprobaciones de calidad en SQL que detectan y corrigen 200 defectos; 15 tests con pytest.
- Hipótesis, baselines y riesgos de data leakage fijados por escrito antes de mirar los datos.
- Con contrato mensual se da de baja el 42,7 % de los clientes; con contrato a dos años, el 2,8 %.

`Python` `pandas` `SQL` `Jupyter` `scikit-learn` `pytest`

### Plataforma GitOps · [sample-api](https://github.com/JavierMolero12/sample-api) + [gitops-manifests](https://github.com/JavierMolero12/gitops-manifests)

De un commit a producción sin ejecutar `kubectl`: un microservicio en FastAPI y todo el camino hasta Kubernetes.

- CI con GitHub Actions: Ruff, pytest y escaneo con Trivy que bloquea vulnerabilidades HIGH y CRITICAL.
- Imagen distroless sin privilegios publicada en GHCR y etiquetada con el SHA del commit.
- Argo CD (App-of-Apps) y Kustomize en dos entornos; producción solo cambia mediante Pull Request.
- Monitorización con Prometheus y un dashboard de Grafana de 8 paneles.

`FastAPI` `Docker` `GitHub Actions` `Trivy` `Kubernetes` `Kustomize` `Argo CD` `Prometheus` `Grafana`

### [Masqchuches Online](https://www.masqchuches.site) · E-commerce en producción

La tienda online de un negocio familiar de chuches y regalos personalizados: catálogo, pagos con Stripe, panel de administración de 12 secciones y un asistente con IA (Gemini) que responde sobre el catálogo real. Repositorio privado.

`Next.js` `TypeScript` `PostgreSQL` `Drizzle ORM` `Auth.js` `Stripe` `Resend` `Railway`

---

## Herramientas

| Área | Herramientas |
| :--- | :--- |
| Datos | Python, pandas, NumPy, SQL (SQLite, PostgreSQL), Jupyter, Excel |
| Machine learning | scikit-learn, feature engineering, evaluación de modelos |
| Visualización | Matplotlib, Seaborn, Plotly, Grafana |
| Desarrollo | TypeScript, Next.js, React, FastAPI, C# y .NET |
| DevOps y cloud | Docker, Kubernetes, Kustomize, Argo CD, GitHub Actions, Prometheus, AWS |

## Formación y certificaciones

- Técnico Superior en Desarrollo de Aplicaciones Web (DAW) · 2025 – 2026
- Técnico Superior en Desarrollo de Aplicaciones Multiplataforma (DAM) · 2023 – 2025
- AWS Knowledge: Cloud Essentials · Blazor: The Complete Guide (.NET 9)

Español (nativo) · Inglés (B1)
