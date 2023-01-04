# Evaluaciones comunes de hipótesis

En estadística, una prueba de hipótesis se utiliza para evaluar y comprender la probabilidad de un punto de vista asumido (hipótesis) basado en datos. 

Usaremos el deporte del fútbol para unos ejemplos, compararemos a la sensación juvenil (Mbappé) con la estrella de los últimos años (ustedes escojan entre Messi y Cristiano).

Vamos a decir que la nueva sensación anotó 8 goles en el mundial y la estrella actual 7.

Un fanático hace el siguiente análisis:

> La nueva sensación parece que es mejor goleador, tiene 24 años y 267 partidos, necesito más información antes de decidir que me volveré fanático suyo a partir de hoy.

## Pruebas para comparar dos futbolistas o dos equipos

Hay varios tipos de pruebas de hipótesis, cada uno para diferentes comparaciones. Para iniciar, necesitamos definir algunas cosas:

1. Hipótesis nula.
2. Hipótesis alternativa.
3. Criterio de aceptación.

La *hipótesis nula* es cuando establecemos nuestro punto de vista inicial. Este punto de vista en estadística es asumir que el resultado es derivado de la casualidad o que no hay relación o asociación con otras variables. Cuando comparemos si son iguales o diferentes dos grupos o individuos, la hipótesis nula siempre será asumir que ambos son iguales.

La *hipótesis alternativa* es esencialmente el punto de vista opuesto a la nula, que el resultado no es una casualidad o decir que si hay una relación entre lo que estamos comparando.

El *criterio de aceptación* es el límite que establecemos que determinará si hay suficiente evidencia para aceptar la hipótesis nula. Usualmente se representa con el p-value de 0.05 (cuando queremos un nivel de confianza de 95% en nuestro análisis, 100% - 95% es 5%).

### T-Test para una muestra

Evalúa las diferencias entre una muestra y el resto de la población.

¿Es el promedio de goles por partido de mi jugador superior al resto de futbolistas?

### T-Test para muestras independientes 

El T-test para muestras independientes evalúa la diferencia entre una muestra (grupo) y otro.

¿Es la posesión de balón promedio de mi equipo superior a la del equipo que voy a enfrentar?
¿Es el promedio de goles por partido de Mbappé superior a la de Messi?

### T-test para muestras emparejadas

Esta prueba evalúa la diferencia de una muestra respecto a sí misma en otro punto en el tiempo.

¿Ha incrementado la distancia promedio recorrida por mi equipo aumentado después de la pretemporada?
¿Ha aumentado la eficiencia para anotar goles de Mbappé con la nueva estrategia del equipo desde la última temporada?

### Prueba de independencia con Chi-cuadrado

Esta prueba evalúa si hay una relación significativa entre dos variables categóricas (posición del futbolista, portero, defensa, mediocampista, delantero), las tipo si/no son un caso especial de las categóricas llamadas de atributos, cómo fue titular en el partido, fue suplente.

La prueba compara la frecuencia actual y la esperada para determinar si hay una dependencia entre ambas variables.

¿El % de efectividad para anotar goles respecto a ocasiones de mi nueva estrella (Mbappé) es más alta que la de jugador estelar de los últimos años (Messi)?

### Cómo interpretamos el p-value

La salida de la prueba de hipótesis, si aceptamos o rechazamos nuestra hipótesis inicial está determinado por el criterio de aceptación, y este lo compararemos con el resultado del p-value.

¿Qué es y qué no es el p-value?

El p-value nos dice si los resultados parecen ser ordinarios o extraños.

Cuando el p-value es menor al criterio de aceptación, entonces descartamos la hipótesis nula y aceptamos la alternativa.

Por ejemplo, si la hipótesis nula es "Messi y Mbappé tienen el mismo rendimiento". La alternativa es "Messi y Mbappé no tienen el mismo rendimiento".
Si el criterio de aceptación es 0.05 y el p-value está entre 0 y 0.049999 entonces la conclusión es, rechazamos la hipótesis nula y decimos.

> Con el 95% de confianza Messi y Mbappé no tienen el mismo rendimiento.

Si la hipótesis fuera, "El promedio de goles de Messi por temporada es superior al de Mbappé", la alternativa seria "El promedio de goles de Messi es menor o igual al de Mbappé".

Si el p-value fuera mayor al criterio de aceptación, digamos 0.1, entonces aceptamos la hipótesis nula, la conclusión sería:

> Con el 95% de confianza, el promedio de goles de Messi **no** es menor o igual al de Mbappé.

Cuando aceptamos la hipótesis nula, se escribe la conclusión negando la hipótesis nula, esto es una convención en estadística.

Hasta la próxima.
