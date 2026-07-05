# Citizen Science Data — notebooks de la CSDA

Notebooks de ejemplo de la **Citizen Science Data Academy (CSDA)** — Fundación
Ibercivis. Un notebook por dataset de la galería pública:

**https://data.ibercivis.es**

## Cómo usarlos

- **Sin instalar nada:** desde la ficha de cada dataset en la galería, el botón
  *"Trabajar en este dataset"* abre el notebook en el JupyterHub de la CSDA
  (https://jupyterhub.ibercivis.es) con los datos ya montados en `/srv/data`.
- **Empezar por el principio:** [`index.ipynb`](index.ipynb).
- **En tu máquina:** clona el repo y descarga los datos desde el enlace Zenodo
  que hay en la cabecera de cada notebook (ajusta la ruta `DATA`).

## Participar

Dudas, resultados y retos: en las
[Discussions](https://github.com/Ibercivis/citizen-science-data/discussions)
de este repositorio.

## Licencias

- Los notebooks se publican bajo **CC-BY-4.0**, salvo los derivados de datasets
  con licencia *ShareAlike* (`marcsi-marine`), que son **CC-BY-SA-4.0**.
- Cada dataset conserva su licencia original, indicada en la cabecera del
  notebook y en su ficha de la galería.

## Mantenimiento

Los notebooks se generan desde plantilla con los metadatos de la galería
(`scripts/generate_notebooks.py` en el repo de la plataforma) y se validan
ejecutándolos contra los datos reales. Para proponer mejoras, abre un issue o
un PR.

---
*Proyecto ECS — T3.4 Citizen Science Data Academy. Servicio sin ánimo comercial.*
