```mermaid
flowchart TD
    A([START]) --> B[/INPUT score1/]
    B --> C[/INPUT score2/]
    C --> D[/INPUT score3/]
    D --> E[PROCESS average = score1 + score2 + score3 / 3]
    E --> F[/DISPLAY average/]
    F --> G([END])
```