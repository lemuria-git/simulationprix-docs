# Moteur de calcul tarifaire

Le calcul suit :

1. Lecture du contexte
2. Lecture des inputs
3. Lecture des référentiels
4. Lecture des barèmes versionnés
5. Génération des combinaisons
6. Application des remises
7. Consolidation dans ResultatPrix

## Logique métier du calcul

PrixFinal = PrixBase × (1 - RemiseCategorie - RemiseConditionCo - RemiseFenetre)

## Gestion du « pas »
Permet d’extrapoler les durées non saisies.

## Résultats
Marquage `IsStandard`, gestion des extrapolations.
