```dataviewjs
dv.table(["Quote", "Author", "Description", "Tags"], dv.pages("#quote")
	.map(p => [p.file.link, p.author, p.description, p.file.tags])
)
```
