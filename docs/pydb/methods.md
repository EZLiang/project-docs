---
title: "A full list of pydb methods"
permalink: /pydb/methods
---
# List of pydb methods
 * `Database(cols:int=0, data:List[List[any]]=None)`: create a database with `cols` columns and
 with data `data`. `data` has precedence over `cols`.
 * `Database.select(*cols: List[int])`: selects the specified columns from the database using zero-based indexes.
 * `Database.filter(expr: str)`: returns a `Database` of all items matching `expr`, where the syntax is described under
 [exparse](../exparse/)

---
[Home](../)