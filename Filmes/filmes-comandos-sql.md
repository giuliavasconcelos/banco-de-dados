# Comandos sql - Referência

# Modelagem física

## Criação da tabela

```sql
CREATE DATABASE filmes CHARACTER SET utf8mb4;
```
<!-- __________________________________________________ -->

# Criar tabela produtos

```sql
CREATE TABLE filmes (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    titulo VARCHAR(45) NOT NULL,
    lancamento YEAR(4) NOT NULL,
    gereno_id INT NOT NULL
);

```
<!-- __________________________________________________ -->

# Criar tabela produtos

```sql
CREATE TABLE genero (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    genero VARCHAR(45) NOT NULL,
);

```

<!--                                                            -->


# Criação da chave estrangeira (relacionamento entre as tabelas)

```sql
ALTER TABLE filmes
    ADD CONSTRAINT fk_generos_filmes

    FOREIGN KEY (genero_id) REFERENCES generos(id)
```

<!-- __________________________________________________ -->

# Apagar uma tabela

```sql
DROP TABLE fabricantes;
```