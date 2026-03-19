# EXPERIMENT-3
## Find all the Toy Story movies 
```sql
SELECT *
FROM movies
WHERE title LIKE 'Toy Story%';
```

## Find all the movies directed by John Lasseter
```sql 
SELECT title, year
FROM movies
WHERE year BETWEEN 2000 AND 2010;
```
## Find all the movies (and director) not directed by John Lasseter
```sql
 SELECT *
FROM movies
WHERE year NOT BETWEEN 2000 AND 2010;
```
## Find all the WALL-* movies
```sql 
SELECT title, year
FROM movies
ORDER BY year ASC
LIMIT 5;
```

