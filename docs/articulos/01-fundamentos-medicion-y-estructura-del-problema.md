# Fundamentos, medicion y estructura del problema

## Proposito

Este articulo desarrolla el suelo conceptual sobre el que descansan casi todas las interpretaciones de la mecanica cuantica. La idea no es repetir un manual de calculo, sino aclarar que piezas del formalismo generan tension y por que la palabra "interpretacion" no es un lujo filosofico, sino una respuesta a problemas muy concretos.

## 1. La pregunta de fondo

La mecanica cuantica funciona extraordinariamente bien. Predice espectros atomicos, tunel, superconductividad, estructura de la materia, correlaciones de entrelazamiento y un largo etcetera. El problema no es que falle como maquina predictiva. El problema es que no esta claro que imagen del mundo debemos extraer de una teoria que:

- usa estados en espacios de Hilbert
- superpone alternativas
- asigna probabilidades con la regla de Born
- permite entrelazamiento no reducible a propiedades independientes

La pregunta central no es "sirve la teoria". Eso esta fuera de duda. La pregunta es "que dice la teoria sobre la realidad, si es que dice algo de ese tipo".

## 2. El formalismo minimo que conviene tener presente

Sin entrar en toda la maquinaria matematica, conviene fijar cinco ideas:

1. El estado cuantico se representa por un vector o funcion de onda.
2. La evolucion de un sistema aislado es unitaria.
3. Los observables se representan por operadores.
4. La regla de Born conecta amplitudes con probabilidades.
5. Los sistemas compuestos admiten entrelazamiento.

Cada una de estas piezas parece inocente por separado. La tension aparece cuando intentamos tomarlas todas juntas y describir una medicion real.

## 3. El choque entre evolucion unitaria y resultado definido

Imagina un sistema de espin preparado en una superposicion:

```text
|psi> = a|arriba> + b|abajo>
```

Si ese sistema interacciona con un aparato ideal de medida, la evolucion unitaria sugiere:

```text
|psi>|listo> -> a|arriba>|aparato-arriba> + b|abajo>|aparato-abajo>
```

La ecuacion de Schrodinger no selecciona un solo termino. Conserva la superposicion. Sin embargo, nuestra experiencia ordinaria es la de un resultado concreto.

Aqui nace el problema de la medicion.

## 4. Estados puros y mezclas: una distincion decisiva

Muchos malentendidos vienen de confundir dos cosas que se parecen formalmente en parte, pero no significan lo mismo:

- un estado puro
- una mezcla estadistica

Un estado puro puede contener coherencias entre alternativas. Una mezcla clasica expresa, en cambio, una distribucion sobre alternativas ya separadas.

La matriz de densidad hace visible esta diferencia. En un estado superpuesto aparecen terminos fuera de la diagonal. Esos terminos son los responsables de la interferencia. En una mezcla clasica no hay coherencia de ese tipo.

Esta distincion importa porque despues de la decoherencia un subsistema puede parecer casi una mezcla clasica, pero eso no significa automaticamente que el mundo haya elegido ya un unico resultado fundamental.

## 5. La cadena de von Neumann

Una medicion se suele modelar como una cadena:

```text
sistema -> aparato -> entorno -> observador
```

El punto delicado es que, en principio, cada eslabon puede tratarse tambien como sistema cuantico. Si el sistema puede estar en superposicion, el aparato tambien puede quedar en superposicion correlacionada. Si el aparato puede tratarse cuanticamente, el observador tambien.

La cadena genera una incomodidad clara:

- si todo es cuantico, la superposicion parece propagarse
- si en algun punto decimos "aqui ya hay un hecho clasico", necesitamos justificar ese corte

De esta tension salen casi todas las familias interpretativas.

## 6. La formulacion compacta del problema

Una manera muy util de plantearlo es notar que las tres afirmaciones siguientes no encajan comodamente a la vez:

1. La funcion de onda describe completamente un sistema individual.
2. La funcion de onda siempre evoluciona linealmente.
3. Las mediciones tienen resultados unicos y definidos.

Las interpretaciones serias suelen escoger una de estas rutas:

- negar que la funcion de onda sea toda la historia
- negar que la evolucion lineal sea exacta siempre
- reinterpretar que significa tener un resultado unico
- negar que el estado cuantico sea una descripcion objetiva literal del sistema

Este esquema es util porque impide que el debate se vuelva vago. Cada familia paga su solucion en un lugar distinto.

## 7. Que hace la decoherencia

La decoherencia es una de las ideas mas importantes del debate contemporaneo. Describe como la interaccion con el entorno suprime de manera rapidisima la interferencia observable entre alternativas macroscopicas.

Su papel es enorme:

- explica por que no vemos con facilidad superposiciones de gatos o punteros
- ayuda a identificar bases estables o casi clasicas
- muestra como aparece una apariencia robusta de mundo macroscopico

La decoherencia explica por que ciertas alternativas dejan de interferir a efectos practicos. Pero no hace, por si sola, todo el trabajo interpretativo.

## 8. Que no hace la decoherencia

Este punto necesita insistencia, porque se confunde constantemente.

La decoherencia no demuestra por si sola que:

- haya un unico resultado absoluto
- la funcion de onda colapse realmente
- el problema de la medicion se haya evaporado
- todas las interpretaciones rivales queden eliminadas

Lo que hace es transformar la estructura dinamica de un sistema abierto de manera que ciertas descripciones clasicas efectivas se vuelvan muy buenas aproximaciones. Eso es muchisimo. Pero no es todavia una ontologia completa.

## 9. El problema de la base preferida

Una superposicion puede escribirse en muchas bases. Sin embargo, los aparatos de medida reales no registran "cualquier" descomposicion matematica. Registran cosas estables, como:

- una aguja a la izquierda o a la derecha
- una marca fotografica
- un pixel encendido o apagado

La pregunta es por que esas variables parecen privilegiadas.

La respuesta fisica moderna apunta a la decoherencia y a la estabilidad frente al entorno. Pero la pregunta ontologica sigue abierta: que estatuto le damos a esa base preferida una vez aparece.

## 10. El problema de los resultados definidos

Supongamos que la decoherencia ya hizo el trabajo de suprimir interferencias observables entre ramas. Todavia queda la pregunta mas punzante:

- por que experimento este resultado
- en que sentido no experimento tambien el otro

Algunas interpretaciones responden con colapso real. Otras con configuraciones ocultas. Otras con ramificacion. Otras con una reinterpretacion del estatus mismo del estado cuantico.

Este es el nucleo donde mas claramente divergen las grandes familias.

## 11. Probabilidad: otro frente, no un detalle menor

Incluso si una interpretacion resuelve o redibuja la medicion, todavia debe explicar la probabilidad.

La pregunta adopta formas distintas segun la familia:

- en teorias deterministas, por que aparece la regla de Born
- en teorias con colapso real, como se justifica la estocasticidad
- en lecturas epistemicas, por que la teoria impone restricciones tan especificas a las creencias

La probabilidad no es un apendice. Es parte del problema central.

## 12. Bell y el fin del localismo clasico ingenuo

Los teoremas de Bell muestran que no podemos reproducir todas las correlaciones cuanticas manteniendo simultaneamente cierto paquete clasico de supuestos:

- localidad fuerte
- valores preexistentes independientes del contexto
- independencia estadistica entre estado profundo y elecciones de medida

Bell no obliga a una unica interpretacion, pero si encarece severamente la esperanza de restaurar una imagen clasica local sin pagar ningun precio conceptual.

Las respuestas tipicas son:

- Bohm acepta no localidad
- Everett mantiene evolucion unitaria sin variables ocultas locales
- QBism y RQM reinterpretan que se esta describiendo
- el superdeterminismo cuestiona la independencia estadistica

## 13. Contextualidad

El teorema de Kochen-Specker pone otro limite profundo: no parece posible asignar valores preexistentes a todos los observables de forma no contextual y coherente con la estructura cuantica.

Esto destruye otra intuicion clasica poderosa: la idea de que una magnitud fisica simplemente "tiene" su valor, con independencia del arreglo total de medida en el que aparece.

La contextualidad no siempre recibe tanta atencion divulgativa como Bell, pero conceptualmente es devastadora para ciertas formas de realismo clasico.

## 14. Psi-ontico y psi-epistemico

Una division muy util del paisaje contemporaneo pregunta que representa exactamente la funcion de onda.

- En una lectura psi-ontica, `psi` representa algo real del sistema.
- En una lectura psi-epistemica, `psi` representa informacion, creencias o restricciones sobre expectativas.

Esta distincion atraviesa el debate de forma transversal:

- Bohm y Everett suelen leerse de forma psi-ontica
- QBism es fuertemente psi-epistemico
- Copenhague admite lecturas mixtas
- algunas propuestas informacionales oscilan entre reconstruccion operativa y ontologia debil

El teorema PBR se ha vuelto relevante precisamente porque pone presion sobre ciertas lecturas epistemicas ingenuas del estado cuantico.

## 15. El amigo de Wigner

El experimento mental del amigo de Wigner fuerza una situacion incomoda. Una persona dentro del laboratorio parece registrar un resultado definido. Pero un observador externo puede describir el laboratorio completo como sistema cuantico aun no colapsado.

Esto presiona tres intuiciones:

- que los hechos medidos son absolutos
- que distintas descripciones deben poder fusionarse sin tension
- que el colapso, si existe, tiene un lugar claro

No es un truco literario. Es una prueba de estres para casi cualquier interpretacion seria.

## 16. El limite clasico

Toda interpretacion debe explicar por que el mundo cotidiano parece tan estable, localizado y compartido. El problema no es solo decir que "a gran escala todo se ve clasico". El problema es explicar por que esa apariencia es:

- robusta
- intersubjetiva
- resistente a pequenas perturbaciones
- eficaz para la ingenieria y la experiencia ordinaria

La respuesta casi nunca depende de una sola idea. Suelen combinarse decoherencia, coarse graining, gran numero de grados de libertad y estabilidad dinamica.

## 17. Criterios razonables para comparar interpretaciones

No existe un criterio unico que decida el debate, pero si hay varios criterios utiles:

- claridad ontologica
- economia dinamica
- capacidad para explicar resultados definidos
- compatibilidad con relatividad
- fertilidad heuristica
- austeridad metafisica
- relacion con la practica experimental

El problema es que rara vez una interpretacion gana en todos a la vez.

## 18. Un ejemplo de intercambio de costes

Vale la pena verlo de forma explicita:

- Everett gana en mantener una sola dinamica universal, pero paga con la multiplicidad de ramas y el problema de la probabilidad.
- Bohm gana en resultados definidos y ontologia clara, pero paga con no localidad y una funcion de onda en espacio de configuracion.
- GRW gana en atacar de frente la medicion, pero paga cambiando la teoria y anadiendo parametros nuevos.
- QBism gana en limpieza epistemica, pero paga adelgazando mucho la ontologia microscopica.

Una buena forma de estudiar interpretaciones es no preguntar demasiado pronto "cual es la verdadera", sino "que problema exacto resuelve mejor cada una y donde traslada el coste".

## 19. Errores de principiante que conviene evitar

### Error 1

Pensar que una interpretacion es automaticamente una nueva prediccion experimental.

### Error 2

Confundir decoherencia con solucion completa del problema de la medicion.

### Error 3

Suponer que Bell "demostro muchos mundos" o "demostro Bohm".

### Error 4

Reducir Copenhague a una frase escolar sobre el observador.

### Error 5

Creer que el debate es vacio porque muchas interpretaciones son empiricamente equivalentes en experimentos ordinarios.

## 20. Preguntas que este articulo deja abiertas

Este texto no pretende cerrar el debate. Pretende afilar las preguntas adecuadas:

- que tipo de cosa es la funcion de onda
- como aparecen resultados definidos
- como entender probabilidad en un mundo cuantico
- que precio estamos dispuestos a pagar por claridad

Esas preguntas son el puente hacia los articulos especializados del repositorio.

## 21. Puentes hacia otros articulos

- Para un desarrollo historico y conceptual de Copenhague y sus parientes, ve a [Copenhague, instrumentalismo y lecturas de conjunto](02-copenhague-instrumentalismo-y-conjunto.md).
- Para una ontologia con variables adicionales y resultados definidos, ve a [Mecanica bohmiana y variables ocultas](03-mecanica-bohmiana-y-variables-ocultas.md).
- Para una teoria universal sin colapso, ve a [Everett, ramificacion y muchos mundos](04-everett-ramificacion-y-muchos-mundos.md).
- Para una solucion dinamica del problema de la medicion, ve a [Colapso objetivo: GRW, CSL y propuestas afines](05-colapso-objetivo-grw-csl-y-afines.md).
- Para enfoques relacionales, epistemicos e informacionales, ve a [Relacional, QBism y enfoques informacionales](06-relacional-qbism-e-informacionales.md).

## Cierre

La pregunta por las interpretaciones de la mecanica cuantica no nace de una aficion exotica por la filosofia. Nace de un hecho simple: el formalismo funciona de una manera que choca con varias intuiciones muy profundas sobre realidad, causalidad, probabilidad y observacion. Comprender ese choque es el primer paso para leer con seriedad el resto del debate.
