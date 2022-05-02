# Demo Testing

Este repositorio contiene el código de una versión simplificada del juego "Quince". Este código fue desarrollado por el equipo docente del curso IIC2113 en su versión 2018-2 ([ver original en GitHub](https://github.com/IIC2113-2018-2/syllabus/tree/master/actividades/AC08)), por Nebil Kawas ([@nebil]) y Rodrigo Saffie ([@rasaffie]).

> En este juego, dos jugadores eligen un número entre el 1 y 9 por turnos (ambos extremos inclusive y sin remplazo). Cada vez que un jugador elige un número, podrá utilizarlo para intentar sumar 15 con los otros números que ya haya elegido. Si un jugador logra sumar 15 con cualquier combinación de números que haya elegido, será el ganador. Notar que es posible que ningún jugador gane si es que no quedan números disponibles.

Este programa contiene los siguientes archivos:

* `quince.py`: Clases para representar cada juego y jugador, con (casi toda) la lógica necesaria para llevar el juego a cabo.
* `tests.py`: Test unitarios implementados con el framework [pytest](https://github.com/pytest-dev/pytest/). Prueba la disponibilidad de los números, que gane el jugador correcto (test a implementar) y que se usen los números correctos para determinar la suma de 15 (test a implementar).

En la rama principal se encuentra el código en su estado inicial, sobre el cual se aplicará testing.

[@rasaffie]: https://github.com/rasaffie
[@nebil]: https://github.com/nebil
