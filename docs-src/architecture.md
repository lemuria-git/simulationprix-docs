# Architecture générale

Le système repose sur quatre couches principales :

[ref.] → [cfg.] → [simu.Input*] → [simu._TmpResultat] → [simu.ResultatPrix] → [pbi.*]


## Rôle de chaque couche

| Couche | Schéma | Description |
|--------|--------|-------------|
| Référentiels | `ref` | Dictionnaires métiers stables |
| Configuration | `cfg` | Barèmes versionnés |
| Simulation | `simu` | Inputs, résultats intermédiaires, résultats finals |
| Exposition BI | `pbi` | Vues optimisées pour Power BI |

Chaque couche est détaillée dans les sections suivantes.
