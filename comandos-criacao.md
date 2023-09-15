# Comandos SQL - Referências
## Modelagem física

### Criar banco de dados 

```sql

CREATE DATABASE vendas CHARACTER SET utf8mb4;

```


<!--                         -->

```sql

CREATE TABLE fabricantes(
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(45) NOT NULL
)

```

<!--                         -->

```sql

CREATE TABLE produtos(
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(45) NOT NULL,
    descricao TEXT(1000) NOT NULL,
    preco DECIMAL(6,2) NOT NULL,
    quantidade TINYINT(4) NOT NULL

)

```

<!--  -->


```sql

ALTER TABLE produtos ADD fabricantes_id INT NOT NULL
AFTER quantidade;

```

<!--                         -->

```sql

ALTER TABLE produtos
# CONSTRAINT é uma restrição definida no relacionamento
ADD CONSTRAINT fk_produtos_fabricantes

# A chave estrangeira deve fazer referência a chave primaria
FOREIGN KEY(fabricante_id) REFERENCES fabricante(id)

```