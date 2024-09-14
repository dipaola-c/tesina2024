
```dataview
Table author as author, publish as "año", tags as tags
WHERE contains(bib,"forreading")
SORT Status DESC
```


```dataview
Table author as author, publish as "año", tags as tags
WHERE contains(bib,"not")
SORT Status DESC
```