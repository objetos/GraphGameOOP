# GraphGameOOP

## Propósito

Implementar el juego de dibujo continuo de línea mediante POO empleando el lenguaje de [Processing](https://processing.org/).

## Objetivos específicos

1. Crear dos modos: juego y creación.
2. En el modo juego, permitir jugar al menos cuatro niveles (cuatro grafos), leyéndolos de la carpeta data y determinando cuando un nivel se completa satisfactoriamente. Las reglas del juego son:
    * Evitar que el jugador una dos nodos para los que no existe un arco.
    * Las líneas se pueden visitar una sola vez (en cualquier sentido).
3. En el modo creación, permitir crear los niveles del juego.
4. Opcionales:
    * Implementar reglas especiales para las líneas: líneas que se deben visitar `n` veces (en cualquier sentido) y líneas que se pueden visitar únicamente en un solo sentido (flechas).
    * Mostrar la solución cuando el jugador se dé por vencido.

### Observaciones

1. Fecha límite: Domingo 6/5/18 a las 24h.
2. Los trabajos son individuales.
3. Los trabajos se deberán exponer en las clases del 7/5/18 y 9/5/18.

### Recomendaciones

1. Mantener la simplicidad, regla de oro de POO.
2. Emplear como punto de partida el [código de la plantilla](https://github.com/objetos/GraphGameOOP/tree/master/GraphGame) que venimos estudiando.
3. Emplear arreglos estáticos siempre que se pueda y `ArrayList` únicamente cuando se juzgue indespensable hacerlo.
4. No importar ninguna herramienta, ni librería externa.
5. Mantener la siguiente jerarquía de archivos para el repositorio:

        GraphGame/
        |-- data/
            |--nivel1.csv
            |--nivel2.csv
            |--nivel3.csv
            |--nivel4.csv
        |-- GraphGame.pde
        |-- (Demás clases, debidamente nombradas)
        |-- README.md
6. Emplear el README.md para discutir lo realizado repecto a los objetivos planteados.
7. Exposiciones
    1. Formato: 5 minutos para presentar + 2 minutos para responder preguntas.
    2. Estructura sugerida
        * Intro (muy breve)
        * Solución propuesta: clases con sus atributos y métodos.
        * Demo y resultados (respecto a los objetivos propuestos).
        * Limitaciones.
