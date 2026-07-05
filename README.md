# Citizen Science Data Hub (CSDH) — notebooks

Example notebooks for the **Citizen Science Data Hub (CSDH)** — Fundación
Ibercivis. One notebook per dataset in the public gallery:

**https://data.ibercivis.es**

> The CSDH is the data platform (gallery + JupyterHub). The training modules of
> the **Citizen Science Data Academy** live on the
> [ECS Academy](https://moodle.citizenscience.eu/) (the *Data Analysis 1-5*
> series: Jupyter, Python, NumPy, Pandas and visualization).

## How to use them

- **Nothing to install:** from each dataset's page in the gallery, the
  *"Work on this dataset"* button opens the notebook in the CSDH JupyterHub
  (https://jupyterhub.ibercivis.es) with the data already mounted at `/srv/data`.
  Sign in with your GitHub account.
- **Start from the beginning:** [`index.ipynb`](index.ipynb).
- **Get the original back after editing your copy:** the *Restore* cell at the
  end of each notebook, or [`restore.ipynb`](restore.ipynb).
- **On your own machine:** clone the repo and download the data from the Zenodo
  link in each notebook's header (adjust the `DATA` path).

## Take part

Questions, results and challenges: in this repository's
[Discussions](https://github.com/Ibercivis/citizen-science-data/discussions).

## Licenses

- Notebooks are published under **CC-BY-4.0**, except those derived from
  datasets with a *ShareAlike* license (`marcsi-marine`), which are
  **CC-BY-SA-4.0**.
- Each dataset keeps its original license, shown in the notebook header and on
  its gallery page.

## Maintenance

Notebooks are generated from a template with the gallery metadata
(`scripts/generate_notebooks.py` in the platform repo) and validated by running
them against the real data. To suggest improvements, open an issue or a PR.

---
*ECS project — T3.4. Non-commercial service.*
