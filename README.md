# Citizen Science Data Hub (CSDH) — notebooks

Notebooks de ejemplo del **Citizen Science Data Hub (CSDH)** — Fundación
Ibercivis. Un notebook por dataset de la galería pública:

**https://data.ibercivis.es**

> El CSDH es la plataforma de datos (galería + JupyterHub). Los módulos
> formativos de la **Citizen Science Data Academy** están en el Moodle de
> Ibercivis.

## Cómo usarlos

- **Sin instalar nada:** desde la ficha de cada dataset en la galería, el botón
  *"Trabajar en este dataset"* abre el notebook en el JupyterHub del CSDH
  (https://jupyterhub.ibercivis.es) con los datos ya montados en `/srv/data`.
  Login con tu cuenta de GitHub.
- **Empezar por el principio:** [`index.ipynb`](index.ipynb).
- **Volver al original tras editar tu copia:** celda *Restaurar* al final de
  cada notebook, o [`restaurar.ipynb`](restaurar.ipynb).
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
*Proyecto ECS — T3.4. Servicio sin ánimo comercial.*
