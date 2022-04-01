# Valores Null Oracle
#### Los valores **Null** son campos de nuestra tabla que no contienen registro ninguno al momento de hacer una consulta pues estos valores se muestran vacios en el resultado que traen.
#### Sin Embargo al momento de configurar estos campos existen reglas de configuracion en donde le indicamos al sistema que no se pueden permitir valores vacion al momento de llenar la tabla a la que se le configure dicha regla.

> Al momento de hacer la configuracion existe dos tipos de funciones que podemos asignar
* [ ] null
  * quiere decir que si admite valores vacios
* [ ] not null
   quiere decir que no admite valores vacios es decir tienes que llenar el dato.
   
```sql
create table libros(
titulo varchar(30) not null,
autor varchar(20) not null,
editorial varchar(15) null,
precio number(5,2);
```
