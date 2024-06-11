![banner](https://github.com/diegocab27/proyecto1/assets/162330383/d1251c1c-916c-4b7c-b57b-cab573e44281)

# PROYECTO 2: Proyecto 2 Sistema de Votación en Javascript

En este proyecto se logra realizar un sistema de votación, donde se puede crear una encuesta con 8 preguntas, cada una con 3 alternativas. El usuario es capaz de votar, ver los resultados en tiempo real y guardar la encuesta ya votada en un array.

Esto fue desarrollado, implementando programación funcional y programación orientada a objetos.

## Autor
- Diego Cabrera Carrasco  [@diegocab27](https://www.github.com/diegocab27)

## Planteamiento

Construir un programa en JavaScript que permita a los usuarios crear encuestas, votar y ver los resultados en tiempo real. El programa debe cumplir con los siguientes requisitos:

- Permitir a los usuarios crear encuestas con opciones de respuesta.
- Permitir a los usuarios votar en las encuestas.
- Mostrar los resultados de las encuestas en tiempo real.
- Almacenar los datos de las encuestas y los votos en una variable.
- Implementar la solución utilizando programación orientada a objetos (POO) o programación funcional (PF).

## Solución explicada paso a paso (PF)

#### 1. Se declara el array `encuesta` y la funcion `crearEncuesta`

Se declara el array `encuesta` donde se almacenaran las preguntas que se iran creando en la funcion `crearEncuesta`. Con un bucle `while` se iran creando las preguntas con un enunciado y 3 opciones hasta llegar a un maximo de 8 preguntas.
