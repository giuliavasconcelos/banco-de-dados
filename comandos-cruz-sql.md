# Comandos SQL - CRUD (Referência)

## Resumo 
C -> Create
R -> Read
U -> Update 
D -> Delete

<!--  -->

## Insert
## Fabricantes

```sql
INSERT INTO fabricantes(nome) VALUES ('Asus');
INSERT INTO fabricantes(nome) VALUES ('Dell');

```

<!--  -->
## Insert
## Fabricantes

```sql
INSERT INTO fabricantes(nome) VALUES ('Asus');
INSERT INTO fabricantes(nome) VALUES ('Dell');
INSERT INTO fabricantes(nome)
VALUES('Apple'),('LG'),('Samsung'),('Brastemp');

```

<!--  -->
## Insert
## Fabricantes

```sql
INSERT INTO produtos(nome, descricao, preco, quantidade, fabricante_id)
VALUES ('Ultrabook', 'Ultrabook Asus Intel Core i9', 6500.99, 7, 1);

INSERT INTO produtos(nome, descricao, preco, quantidade, fabricante_id)
VALUES ('Geladeira', 'Frost-Free com acesso a internet', 8500.99, 10, 6);

INSERT INTO produtos(nome, descricao, preco, quantidade, fabricante_id)
VALUES ('Iphone 14 Pro Max', 'Processador Bionic com 516GB de armazenamento', 9999.97, 3, 3
);

INSERT INTO produtos(nome, descricao, preco, quantidade, fabricante_id)
VALUES ('Ipad Mini', 'Tablet com tela de retina 4k com 512Gb de armazenmento', 5000, 8, 3
);

```

<!--  -->

## Insert
## Fabricantes

```sql
INSERT INTO fabricantes(nome) 
VALUES ('Positivo'),('Microsoft');

```
<!--  -->

## Insert
## Fabricantes

```sql
INSERT INTO produtos(nome, descricao, preco, quantidade, fabricante_id)
VALUES ('Xbox', 'Console de última geração', 2500, 6, 8
);

INSERT INTO produtos(nome, descricao, preco, quantidade, fabricante_id)
VALUES ('Ultrabook', 'AMD Ryzen 5 16Gb RAM...',4500.97, 12, 7
);

```