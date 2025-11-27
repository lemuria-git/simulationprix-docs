# Annexes

## Exemple SQL

```sql
SELECT *
FROM simu.ResultatPrix
WHERE SimulationId = 202511;

Exemple Power Apps

Set(
  _res,
  SimulationPrix_8.simuspGetDefaultPrixForfait({
    ExerciceId: 1,
    GroupePoolId: 2,
    PeriodeId: 1
  })
);
ClearCollect(colPrix, _res.ResultSets.Table1);
