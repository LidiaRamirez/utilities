# CSS

## Buenas prácticas

* No usar `margin: 0 auto` para no comprometer el margin top y margin bottom para centrar 
~~~
.item { 
  margin-left: auto;
  margin-rigth: auto;
}
~~~
* Para que se tome el valor asignado 
~~~
* {
  box-sizing: border-box;
}
~~~
* Hack elementos tengan margin-bottom pero un elemento especifico este pegado a otro 
~~~
[class^="box-"] {
  margin-bottom: 20px;
}

.box-2 {
  margin-top: -20px;
}
~~~
