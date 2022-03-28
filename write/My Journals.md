#to-migrate 
```dataviewjs
dv.table(["Article", "Description", "Tags", "Date"], dv.pages("#journal")
	.sort(p => p.date)
	.map(p => [p.file.link, p.description, p.file.tags, p.date])
)
```
