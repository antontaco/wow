# Druida - Restauraci�n



#### `Acechar`

* Independientemente de la forma actual en la que te encuentres, quedar�s en forma felina y en sigilo

```
#showtooltip
/cancelform [noform:2]
/cast Acechar
```



#### `Alivio presto` o `Alivio presto` + `Resguardo de Cenarius` ambos con overmouse

* Al ubicar el rat�n sobre un jugador aliado o sobre una barra de salud aliada del interfaz, ejecutar� `Alivio presto` o `Resguardo de Cenarius`.
* Al tener seleccionado un jugador aliado, ejecutar� `Alivio presto` o `Resguardo de Cenarius`.
* En cualquier otro caso, ejecutar� `Alivio presto` o `Resguardo de Cenarius` sobre ti.

```
#showtooltip
#showtooltip Alivio presto
/castsequence [@mouseover,help,nodead,talent:1/2][help,nodead,talent:1/2][@player,talent:1/2] reset=29 Alivio presto, Resguardo de Cenarius
/cast [@mouseover,help,nodead][help,nodead][@player] Alivio presto
```

> Es interesante cambiar el orden de ejecuci�n de `Alivio presto` y `Resguardo de Cenarius` si tienes el legendario [Edraith](http://es.wowhead.com/item=137095/edraith-ataduras-de-aglaya&spec=105) para realizar un `Resguardo de Cenarius` un 120% m�s fuerte.



#### `Cura de la Naturaleza` con overmouse

* Al ubicar el rat�n sobre un jugador aliado o sobre una barra de salud aliada del interfaz, ejecutar� `Cura de la Naturaleza`.
* Al tener seleccionado un jugador aliado, ejecutar� `Cura de la Naturaleza`.
* En cualquier otro caso, ejecutar� `Cura de la Naturaleza` sobre ti.

```
#showtooltip
/use [@mouseover,help,nodead][help,nodead][@player] Cura de la Naturaleza
```



#### `Rejuvenecimiento` con overmouse o `Fuego solar`

* Al ubicar el rat�n sobre un jugador aliado o sobre una barra de salud aliada del interfaz, ejecutar� `Rejuvenecimiento`.
* Al tener seleccionado un jugador aliado, ejecutar� `Rejuvenecimiento`.
* Al tener seleccionado un enemigo, ejecutar� `Fuego solar(Solar)`.
* En cualquier otro caso, ejecutar� `Rejuvenecimiento`.

```
#showtooltip
/use [@mouseover,help,nodead][help,nodead] Rejuvenecimiento
/use [harm] Fuego solar(Solar); Rejuvenecimiento
```

> Con esta macro puedes sacarte todos los hechizos de da�o bindeados a curas
>
> Es muy interesante si tienes el legendario [Promesa de Elune](http://es.wowhead.com/item=137023/promesa-de-elune-diosa-de-la-luna&spec=105) (De Equilibrio) bindearte tambi�n  `C�lera Solar` a alg�n hechizo (Recomiendo a `Toque de sanaci�n` debido que llegar�s a disparar alguna que otra sanaci�n pensando que est�s atacando y este hechizo es el que menos man� consume)









