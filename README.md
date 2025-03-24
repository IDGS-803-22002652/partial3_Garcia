La base de datos utilizada es esta:
drop database if exists pizzas; 
create database pizzas;
use pizzas;	

Describe pizza;
describe Clientes;
describe pedidos;

SELECT*FROM pizza;
SELECT*FROM cliente;
SELECT idVenta,idPedido,idCliente,fechaVenta,montoTotal FROM ventas;
SELECT*FROM User;

drop table User;

create table User(
id int auto_increment primary key not null,
username varchar(20) not null,
password char(200) not null
);

INSERT INTO User (username,password) VALUES ('Omar','scrypt:32768:8:1$c9lPBjYDb6jtDBcR$d61da242934352657bd7245f7bec1939642aa0a34fd25f89871b42ba1da3fc9b406786295b416c3fc20f3bc2b2fafa0a91a3c932ef0590ca5e00eda32aef23ef');

Y el Usuaario y Contraseña de la practica son:
-Omar
-12345
