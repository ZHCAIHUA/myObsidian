```dataview
LIST
FROM "📆 Activity"
```

```dataview
LIST
WHERE file.mtime >= date(today) - dur(1 week)
```


```dataview
TABLE workout
FROM "2️⃣ Collections"
SORT file.ctime DESC
LIMIT 14
```