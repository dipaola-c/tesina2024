#hidden_from_graph
### Por leer

```dataview
Table author as author, publish as "año", tags as tags
WHERE contains(bib,"forreading")
SORT Status DESC
```


### Descartadas

```dataview
Table author as author, publish as "año", tags as tags
WHERE contains(bib,"not")
SORT Status DESC
```