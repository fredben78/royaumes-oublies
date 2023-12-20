# Cormyr Lieux
```dataview
table Type, Lord, Population, Force-armee, Lord, Temple-majeur, Nobles-locaux
where contains(tags, "lieu") and contains(regions, "Cormyr")
sort Population DESC
```

# Cormyr PNJ/Famille


```dataview
table Type 
where contains(Type, "PNJ") or contains(Type, "Famille") and contains(regions, "Cormyr")
sort type ASC
```
