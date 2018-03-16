# Taller-Python
**Contenidos a tratar**
**Gestion de Proyectos**
+ virtualenv
+ pipfile
+ pyenv
+ pipenv

**Organizacion de modulos**
  
* `__init__.py`
  
* `__main__.py`

**Orientacion a objetos**  
* Introduccion  
* Decoradores e importancia  
* Uso de property(s)  

**Estructuras de datos y rendimiento**  
* Listas  
* Maps  
* Diccionarios  
* List Comprenhension  



## Resumen del taller

**Parte 1- Gestión de proyectos**  
Una vez explicado los distintos métodos de gestión de proyectos, y creado uno con pipenv se procederá a la creación de una aplicación
En primer lugar se creará la clase FakeMonster, en un módulo separado para su exportación posterior  esta clase tendrá las siguientes propiedades:
   + *name - Nombre del monstruo*
   + *level - Nivel del monstruo*
   + *picture - Imagen del monstruo*
   + *location - Localizacion en Lat/Long del digimon para su posterior uso en un mapa*

**Parte 2- Orientacion a objetos**  
Una vez creado el modulo y probada su exportación, se pasará a la segunda parte donde se explicará la orientación a objetos.
Ahí se creará una clase llamada *Digimon* que hereda de *FakeMonster*, con los siguientes requisitos:
  + *El nombre del digimon deberá terminar con el sufijo "mon" (Ej: Agu -> Agumon)*
  + *El nivel (level) deberá ser un string en el siguiente conjunto de niveles [Baby, Rookie, Champion, Mega, Hyper]*
  + *El digimon contendrá un método, llamado digivolve, con dos parámetros, un nuevo nombre y un nivel de los citados anteriormente. Este método cambia su nombre original y su nivel.*
  
Una vez creada, se creará otra clase *Pokemon* que hereda de *FakeMonster* con los siguientes requisitos:
 + *Cualquier nombre es valido pero no pude terminar en "mon"*
 + *El nivel (level) es un entero comprendido entre 1 y 100*
 
Posteriormente se explican los decoradores y las properties  
Se dice que los Pokemon van a intentar hacerse pasar por Digimons para "colarse en el mundo real" por lo que tendremos que hacer uso de los decoradores para ello, es decir, ***sin modificar la clase hay que lograr que "Pikachu" sea "Pikachumon" y que si su nivel es 25 aparezca como Rookie***.


**Parte 3 - Estructuras de datos y perfomance**  
En la tercera parte se proporcionaran dos ficheros de texto `pokemon.txt`, y `digimon.txt` con los datos a insertar, estos estaran en texto plano, por lo que habrá que parsearlos.
Se plantearán diferentes alternativas de almacenamiento, empezando por las listas, list comprenhesion,  continuando por los **diccionarios** y finalizando con el uso de la función map.

Finalmente y usando **Jupyter y Mapbox** se usará para mostrar los distintos digimons y pokemons disfrazados en geojson, con ello **concluiría el taller**.


 

 
