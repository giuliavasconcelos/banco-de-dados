# Comandos SQL - CRUD (Referência)

## Resumo 
C -> Create
R -> Read
U -> Update 
D -> Delete

<!--  -->

## Insert
## Generos

```sql
INSERT INTO genero(genero) VALUES ('Comédia');
INSERT INTO genero(genero) VALUES ('Ação');
INSERT INTO genero(genero)
VALUES('Suspense'),('Terror'),('Aventura'),('Ficção Cientifica');

```

<!--  -->
## Insert
## Filmes

```sql
INSERT INTO filmes (titulo, lancamento, genero_id)
VALUES ('Albergue', '2005', 4);

INSERT INTO filmes (titulo, lancamento, genero_id)
VALUES ('Top Gun Maverick', '2022', 2);

INSERT INTO filmes (titulo, lancamento, genero_id)
VALUES ('Se beber não case', '2009', 1);


```

