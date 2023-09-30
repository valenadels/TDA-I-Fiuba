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

Tendría que ver siempre para mi día siguiente o mis dos subsecuentes días no se bien eso
Sabiendo que siempre el último día entreno, como llegue al n-1
- Habiendo entrenado el día anterior teniendo cierta energía disposible s_i
    - si el día anterior no entrenaba, hoy tenía una ganacia mayor?
- No habiendo entrenado teniendo disponible s1
    - si el día anterior entrenaba, la ganancia era mayor? porque quuizas s2 es <= a la ganacia posible de mi ultimo día 

Similitud con la mochi es que cada día en este caso tiene ua ganancia. Podrpiamos decir que es tipo el problema de la mochia pero restringido a que 
nos elementos tienen cierto orden y a medida que avanzo en los días los anteriores se descartan



## Necesitamos
1. Encontrar la forma de mis subproblemas
   - A medida que avanzo, mis problemas son más pequeños
   - Resolver el problema para 2 días es más fácil que para 3 días y así
2. La forma en que dichos subproblemas se componen para solucionar subproblemas más grandes