# PROYECTO-ETL
![portada](https://github.com/Barge7/PROYECTO-ETL/blob/main/data/portada.jpg)

## Introducci贸n

Se decide crear una base de datos sobre perros en adopci贸n a partir del scraping en diferentes webs.馃攷


## Scraping

### La primera web pertenece a la protectora El Refugio.
![refugio1](https://github.com/Barge7/PROYECTO-ETL/blob/main/data/elrefugio1.jpg)
  
Se realiza scraping mediante Selenium WebDriver de los diferentes perros en adopci贸n,  
obteniendo datos como el nombre, el sexo, la raza, el tama帽o, la edad, la foto y el link.馃惗  

Los datos obtenidos se limpian y clasifican, adem谩s se a帽ade una columna con el ID  
de la protectora a la que pertenece para posibles futuras agrupaciones y consultas.
Se obtiene una tabla con 72 filas y 9 columnas.  

![refugio2](https://github.com/Barge7/PROYECTO-ETL/blob/main/data/elrefugio2.jpg)

  
    

### La segunda web pertenece a la protectora ACUNR.  

![ACUNR1](https://github.com/Barge7/PROYECTO-ETL/blob/main/data/acunr1.jpg)  

La realizaci贸n del scraping es mediante Selenium WebDriver.  

Se obtienen datos de los diferentes perros en adopci贸n e informaci贸n como  
la edad, la raza, el sexo, el tama帽o, antecedentes de salud y el caracter.馃悤  
A esta tabla tambien a帽adimos una columna con el ID de la protectora.  
Se obtiene una tabla con 52 filas y 9 columnas.  
  
  


### La tecera fuente de informaci贸n se decide que sea una interfaz de programaci贸n de aplicaciones (API), dedicada a las diferentes razas de perros y sus caracter铆sticas.   

Se obtiene una tabla de 172 filas y 7 columnas.  

![breed](https://github.com/Barge7/PROYECTO-ETL/blob/main/data/breed.jpg)

