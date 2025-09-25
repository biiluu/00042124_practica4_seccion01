# 00042124_practica4_seccion01
Pregunta p8
Analicemos ¿Qué ocurre en cada caso presentado anteriormente con los operadores y porqué JS me permite esto?

R// JavaScript permite este tipo de operaciones porque sigue reglas matemáticas y ofrece flexibilidad en la manipulación de variables. En el ejemplo, primero se asignan los valores 1, 2 y 3 a las variables x, y y z. A partir de ahí, se aplican diferentes operadores de asignación compuesta.
Cuando se escribe x = y, la variable x pasa a tener el valor de y, quedando en 2. Después, al aplicar x += z, se está sumando el valor de z al de x, lo cual es equivalente a escribir x = x + z, dando como resultado 5. De la misma manera, x -= y resta el valor de y al de x y se obtiene 3; x *= z multiplica a x por z, quedando en 9; x /= y divide a x entre y, lo que produce 9/2; y finalmente x %= x calcula el residuo de dividir x entre sí mismo, que siempre es 0.

En general, cada uno de estos operadores compuestos (+=, -=, *=, /=, %=) representa una forma abreviada de escribir expresiones más largas, como x = x + y o x = x - y. Gracias a esta sintaxis abreviada, el lenguaje permite escribir operaciones de manera más simple y legible sin perder su significado matemático.

Pregunta p9
Analicemos ¿El comportamiento de los flujos de control es similar a otros lenguajes y ambientes de desarrollo?

R//El comportamiento de los flujos de control sigue la misma lógica en la mayoría de lenguajes y entornos de desarrollo, ya que todos se basan en principios fundamentales. Un ejemplo de esto es la estructura if: si la condición evaluada resulta verdadera, se ejecuta la acción definida en su bloque; en caso contrario, se pasa al bloque else, donde se realiza la acción alternativa. Esta lógica es universal y no varía de un lenguaje de programación a otro.