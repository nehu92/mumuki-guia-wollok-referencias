Hasta ahora venimos insistiendo en que en objetos le enviamos mensajes a los objetos. ¡Y no mentimos!

Sucede que en realidad las cosas son un poco más complejas, y no conocemos a los objetos directamente, sino a través de etiquetas llamadas _referencias_. Entonces cuando tenemos una declaración de variable como ésta: 

```wollok
var saludo = "hola"
```

lo que estamos haciendo es _crear una referencia_ que _apunta_ al objeto `"hola"`.


Y cuando le enviamos un mensaje: 

```wollok
saludo.toUpperCase()
```

le estamos el mensaje `toUpperCase()` al objeto `"hola"`, a través de la referencia `saludo`, que es una variable. 


> Veamos si se entiende hasta acá: creá una variable llamada `despedida` que apunte al objeto `"adios"`, y enviale el mensaje `size()`. 