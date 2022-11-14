# PROYECTO-ETL
![portada](https://github.com/Barge7/PROYECTO-ETL/blob/main/data/portada.jpg)

## Introducción

Se decide crear una base de datos sobre perros en adopción a partir del scraping en diferentes webs.🔎


## Scraping

### La primera web pertenece a la protectora El Refugio.
![refugio1](https://github.com/Barge7/PROYECTO-ETL/blob/main/data/elrefugio1.jpg)
  
Se realiza scraping mediante Selenium WebDriver de los diferentes perros en adopción,  
obteniendo datos como el nombre, el sexo, la raza, el tamaño, la edad, la foto y el link.🐶  

Los datos obtenidos se limpian y clasifican, además se añade una columna con el ID  
de la protectora a la que pertenece para posibles futuras agrupaciones y consultas.
Se obtiene una tabla con 72 filas y 9 columnas.  

![refugio2](https://github.com/Barge7/PROYECTO-ETL/blob/main/data/elrefugio2.jpg)

  
    

### La segunda web pertenece a la protectora ACUNR.  

![ACUNR1](https://github.com/Barge7/PROYECTO-ETL/blob/main/data/acunr1.jpg)  

La realización del scraping es mediante Selenium WebDriver.  

Se obtienen datos de los diferentes perros en adopción e información como  
la edad, la raza, el sexo, el tamaño, antecedentes de salud y el caracter.🐕  
A esta tabla tambien añadimos una columna con el ID de la protectora.  
Se obtiene una tabla con 52 filas y 9 columnas.  
  
  


### La tecera fuente de información se decide que sea una interfaz de programación de aplicaciones (API), dedicada a las diferentes razas de perros y sus características.   

Se obtiene una tabla de 172 filas y 7 columnas.  

![breed](https://github.com/Barge7/PROYECTO-ETL/blob/main/data/breed.jpg)

