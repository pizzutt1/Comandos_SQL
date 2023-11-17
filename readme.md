# Comando SQL

* para executar os comandos pressione CTRL + Enter

### criar database
```
create database nome_base
```
### criar database
```

use nome_base
```

### criar tabela de usuários
```
create table usuarios(
	id int not null auto_increment,
    nome varchar(120) not null,
    email varchar(120) not null,
    senha varchar(120) not null,
    data_nas date,
    primary key(id)
);
```

### insert 
```
INSERT INTO usuarios(nome, email, senha, data_nas)
VALUES ('Taylor Swift', 'tstheeras@gmail.com', 'secreta', '1989-12-13');
```
### Listar dados
```
select * from usuarios
```
