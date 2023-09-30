## PLANTEO DEL TP
Para pasar en limpio el TP, lo que piden, condiciones, etc.

## Datos
- n días de entrenamiento
- Entrenamiento del dia i demanda un esfuerzo ei. Definimos la ganancia como gi tal que
  gi = ei
- Entrenamiento del dia i es inammovible, es decir, no se puede cambiar.
- Cantidad de energia que se puede gastar en un dia i es j
- Si j < ei, gi = j sino gi = ei (nota: si j>ei no hay más ganacia que ei)
- La cantidad de energia del día disminuye a medida que pasan los entrenamientos.
  El primer día luego de descansar, la cantidad de energia es s1
  El segundo día luego de descansar, la cantidad de energia es s2
  .... s1>=s2>=....>=sn
- Si se descansa un dia, la cantidad de energia se recupera a s1. Si se descansa dos dias, la cantidad de energia se recupera a s1 siempre, etc. No se puede tener nunca más energía que s1. Si descanso, siempre vuelvo a s1.
  (nota: si se descansa un día, el entrenamiento de ese día NO se hace => NO hay ganancia)

## Caso base
- Si n = 0, la ganancia es 0
- Si n = 1, la ganancia es s1


## n-1
Vino Messi y me dice que hasta el día n-1 tengo todo resuelto => hasta el día n-1 entrene de la mejor forma posible obteniendo el máximo de ganancia.

¿Cuando se reduce mi problema?

¿Entreno ese dia o no entreno?
- el ultimo dia siempre se entrena
- Minimo tengo s1
- Al elegir si entreno o no tengo que ver si descansando obtengo mas ganancia al dia siguiente
- Cuando tengo 1 día -> todo ok entreno ese día y obtengo la ganacia correspond

si entreno es ese valor más lo que ya tenía 