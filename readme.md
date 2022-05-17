## Practica Postgresql

Para la relizacion de asta practica se debera tener instalado [Postgresql](https://www.postgresql.org/), consulta como debera ser su instalacion segun tu S.O. con el que trabajes.

1. Abrimos nuestra linea de comando `SQL Shell` o en su caso en la cmd con el comando: `psql`. 
Nos pedira que nos loguemos de acuerdo a las credenciales dadas en la instalacion. 
![Texto alternativo](https://github.com/jorgealexis07/Practica_PostgreSQL/blob/master/img/1login%20psql%20sql%20shell.PNG)

2. Ejecutamos el comando `\l` para ver todas las bases de datos locales.
![Texto alternativo](https://github.com/jorgealexis07/Practica_PostgreSQL/blob/master/img/2listbdlocales.PNG)

3. Creamos nuestra BD con el siguiente comando:
    `create database <name_database> ;`
![Texto alternativo](https://github.com/jorgealexis07/Practica_PostgreSQL/blob/master/img/3creabd.PNG)

4. Seleccionamos nuestra BD con el siguiente comando:
    `\c <name_database> ;`
![Texto alternativo](https://github.com/jorgealexis07/Practica_PostgreSQL/blob/master/img/4seleccionBD.PNG)

5. Creamos una tabla con:
![Texto alternativo](https://github.com/jorgealexis07/Practica_PostgreSQL/blob/master/img/5createtable.PNG)

6. listamos la tabla que acabamos de crear:

![Texto alternativo](https://github.com/jorgealexis07/Practica_PostgreSQL/blob/master/img/6listartables.PNG)

7. Realizamos las siguientes inserciones a la tabla `explorers`.
![Texto alternativo](https://github.com/jorgealexis07/Practica_PostgreSQL/blob/master/img/7Inserciones.PNG)

8. Leemos los registros de la tabla `explorers` con el siguiente comando:
`select * from <name_table> `
![Texto alternativo](https://github.com/jorgealexis07/Practica_PostgreSQL/blob/master/img/leer%20registros%20de%20la%20tabla.PNG)

9. Leemos solo el nombre de los registros de la tabla `explorers` con el siguiente comando:
     `select e.username from explorers e;`
![Texto alternativo](https://github.com/jorgealexis07/Practica_PostgreSQL/blob/master/img/lee%20solo%20los%20nombres%20de%20los%20registros%20de%20la%20bd.PNG)

10. Actualizamos el registro con el siguiente comando `update explorers e set username = 'Explorer 1 Upd' where e.id = 1;`: 
![Texto alternativo](https://github.com/jorgealexis07/Practica_PostgreSQL/blob/master/img/actualizacion.PNG)

11. Eliminamos el registro con el siguiente comando `delete from explorers e where e.id = 1;`: 
![Texto alternativo](https://github.com/jorgealexis07/Practica_PostgreSQL/blob/master/img/eliminar%20registros.PNG)

Listo hemos acabado la practica.

Con esta practica hemos logrado:

- Instalar Postgresql
- Usar la línea de comando de Postgresql
- Crear un db desde la terminal
- Crear un tabla desde la terminal
- Aprender a realizar las operaciones básicas: crear, actualizar, leer y eliminar.
