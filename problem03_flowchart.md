```mermaid
flowchart TD
    A([START]) --> B[/INPUT nbprice/]
    B --> C[/INPUT nbquantity/]
    C --> D[PROCESS itemtotal = nbprice * nbquantity]
    D --> E[/DISPLAY itemtotal/]
    E --> F([END])
```