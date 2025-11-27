# SimulationPrix – Documentation Officielle

Ce dépôt contient **la documentation fonctionnelle et technique complète** du projet **SimulationPrix**.

## Structure
La documentation est générée sous forme de **site statique** à l'aide de **MkDocs + Material**, un framework moderne permettant une navigation fluide, une recherche instantanée et une mise en page professionnelle.

simulationprix-docs/
├── mkdocs.yml
├── README.md
└── docs/



## Aperçu du contenu
- Architecture globale du modèle
- Référentiels (schéma `ref`)
- Configuration tarifaire (schéma `cfg`)
- Simulation (schéma `simu`)
- Moteur de calcul tarifaire
- Intégration Power Apps
- Exposition dans Power BI
- Flux de données complet
- Annexes & exemples SQL/Power Apps

## Lancer le site en local

```bash
pip install mkdocs-material
mkdocs serve
