# EXPERIMENT-3
## Find all the Toy Story movies 
```sql
SELECT *
FROM movies
WHERE title LIKE 'Toy Story%';
```

## Find all the movies directed by John Lasseter
```sql 
SELECT *
FROM movies
WHERE director LIKE 'John lasseter%';
```
## Find all the movies (and director) not directed by John Lasseter
```sql
SELECT *
FROM movies
WHERE director NOT LIKE 'John lasseter%';
```
## Find all the WALL-* movies
```sql 
SELECT *
FROM movies
WHERE title LIKE 'WALL-%';
```

