# ComputeGridValue

```csharp
public int ComputeGridValue(char[,] grid, char player)
```

scoreForTwoInRow = 10;
scoreForThreeInRow = 100;
scoreForFourInRow = 1000;

input: grille 2d - Player = "X" 
Output: Valeur de la grille 

parcour chaque cellule et vérifie les alignements possibles dans des directions définies.

```csharp
if (newRow >= 0 && newRow < rowCount && newCol >= 0 && newCol < colCount)
```
Empeche de sortir de la grille quand on cherche dans une direction