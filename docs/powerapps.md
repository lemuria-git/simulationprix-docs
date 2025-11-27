# Power Apps

Power Apps sert à :

- créer une simulation,
- saisir des prix,
- déclencher le calcul,
- afficher les résultats.

## Contexte transmis par Power BI
PowerBIIntegration.Data inclut :
ExerciceId, PeriodeId, GroupePoolId, TypeProduitId, etc.

## Création d’une simulation
INSERT dans `simu.Simulation`, avec récupération du SimulationId.

## Saisie
UPSERT dans `simu.InputForfait` ou `simu.InputBillet`.

## Calcul
Appel d'une procédure stockée SQL.

## Visualisation
SELECT sur `simu.ResultatPrix`.
