> [!important] 1. Composición de la obra de Seminario
> 2. Un tema de tesina en relación a alguna problemática ejemplificada en la obra compuesta.
> 3. Referencias y análisis en al menos una obra de repertorio en la que se ejemplifica el tema de tesina.
> 4. Un auto-análisis de la obra compuesta en relación al te
## Bibliografía

```dataview
Table author as author, publish as "año", tags as tags
WHERE contains(bib,"read")
SORT Status DESC
```

## Obras

```dataview
Table author as author, publish as "año", tags as tags
WHERE contains(type,"obra")
SORT Status DESC
```
