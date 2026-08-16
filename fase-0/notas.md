## Trazado de búsqueda binaria

Arreglo: [2, 5, 8, 12, 16, 23, 38, 45, 56, 67, 72, 80, 91, 97, 99]
Objetivo: 23

| Iteración | izq | der | medio | valor  | Acción         |
|-----------|-----|-----|-------|--------|----------------|
| 1         | 0   | 14  | 7     | 45     | 45 > 23 → der = 6 |
| 2         | 0   | 6   | 3     | 12     | 12 < 23 → izq = 4 |
| 3         | 4   | 6   | 5     | 23     | Encontrado     |