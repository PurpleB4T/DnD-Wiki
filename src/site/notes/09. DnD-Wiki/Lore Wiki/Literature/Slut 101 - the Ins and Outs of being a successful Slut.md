```dataview
> TABLE join(aliases, ", ") AS Aliases, quicknote AS Notes
> FROM #Letter 
> WHERE econtains(holder, this.file.link)
> SORT file.name ASC

> [!metadata|literature]- Literature
> ```