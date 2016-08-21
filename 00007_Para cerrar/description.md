Cerremos con un último problema: Jasmín toca el piano familiar, pero con el uso se va desafinando, y Lucio, el afinador, tiene que afinarlo. En particular: 

* cada vez que Jasmin toca, el nivel de afinación del piano (inicialmente en 100) baja en un 1%
* el piano esta afinado si su nivel de afinación está por encima del 80%
* cada vez que Lucio afina al piano, su nivel de afinación aumenta tanto como tiempo le dedique: 5% por cada hora. Y nunca se pasa del 100%, claro. 

> Desarrollá los objetos necesarios para que podamos hacer lo siguiente: 
> 
> ```wollok
> jamin.piano(pianoFamiliar) //configura al piano de jasmin
> jamin.tocar()
> pianoFamiliar.estaAfinado() //true o false
> lucio.afinar(pianoFamiliar, 3)//lo afinadurante 3 horas
```
