# Simulation (`simu.*`)

La couche simulation stocke :

- le contexte (simu.Simulation),
- les entrées (simu.InputForfait, simu.InputBillet),
- les résultats intermédiaires (simu._TmpResultat),
- les résultats finals (simu.ResultatPrix).

## simu.Simulation
Entête : type produit, période, exercice, version règles, périmètre.

## simu.InputForfait
7 prix standards + pas.

## simu.InputBillet
Prix unitaires.

## simu._TmpResultat
Combinaisons générées automatiquement.

## simu.ResultatPrix
Résultats consolidés.

---
**Pivot du système :** `SimulationId`.
