# Lección 2: Variables y tipos de datos (8 minutos)

## Notas para el profesor

* Esta es la primera lección con código — es normal que algunos se pongan nerviosos. Tranquilízalos desde el inicio.
* Usa analogías del mundo real para explicar variables antes de mostrar código. Que entiendan el concepto primero, el código después.
* En la parte práctica, explica cada línea mientras la escribes — no escribas bloques enteros en silencio.
* Al mostrar el código completo al final, dales un momento para que lo escriban ellos en su computadora.
* El código de esta lección es la primera pieza del videojuego — recuérdales eso, que ya están construyendo algo real.

## Guión

**[APERTURA]**

"Muy bien, arrancamos con lo primero que necesita cualquier programa: guardar información. Y para eso existen las variables."

**[SUBTEMA 1 — ¿Qué es una variable y para qué sirve?]**

"Imaginen que tienen una caja. Le ponen un nombre a esa caja, meten algo adentro, y cada vez que necesitan ese algo, solo dicen el nombre de la caja. Eso es una variable — una caja con nombre donde guardamos información."

"En nuestro videojuego, vamos a necesitar guardar cosas como: ¿cómo se llama el personaje? ¿Cuánta vida tiene? ¿Cuánto daño hace con su ataque? Toda esa información va en variables."

**[SUBTEMA 2 — Tipos de datos básicos]**

"Pero no todas las cajas son iguales. En Java, dependiendo de qué tipo de información vas a guardar, usas un tipo de dato diferente. Los más importantes para hoy son estos cuatro:"

"int — para números enteros. La vida del personaje, el daño, el nivel. Todo número sin decimales."

"String — para texto. El nombre del personaje, un mensaje en pantalla. Siempre va entre comillas."

"double — para números con decimales. Si algún día quieren calcular un porcentaje de daño, por ejemplo."

"boolean — solo puede ser verdadero o falso. ¿El personaje está vivo? Sí o no. Eso es un boolean."

**[SUBTEMA 3 — Cómo declarar y asignar variables en Java]**

"En Java, para crear una variable escribimos primero el tipo, luego el nombre, luego el valor. Así:"

"int vida = 100; — aquí le estamos diciendo a Java: crea una caja de tipo entero, llámala vida, y mete adentro el número 100."

"Simple, ¿verdad? El punto y coma al final es obligatorio en Java — es como el punto al final de una oración. No lo olviden."

**[PARTE PRÁCTICA — Construimos: las primeras variables del juego]**

"Ahora sí, manos al código. Voy a escribir en vivo las primeras líneas de nuestro videojuego, y quiero que me sigan línea por línea."

**[El profesor escribe en vivo, explicando cada línea:]**

***
// Variables de nuestro personaje

String nombrePersonaje = "Guerrero";

int vida = 100;

int ataque = 15;

System.out.println("Nombre: " + nombrePersonaje);

System.out.println("Vida: " + vida);

System.out.println("Ataque: " + ataque);
***

"Línea por línea: primero definimos el nombre — un String porque es texto. Luego la vida — un int, porque es un número entero. Luego el ataque — otro int."

"Y al final le decimos a Java que imprima esa información en pantalla con System.out.println. Eso es lo que verá el jugador."

**[El profesor muestra el código completo y el resultado en pantalla:]**

"Aquí está todo junto. Tómate un momento para escribirlo en tu computadora exactamente como lo ves. No copies y pegues — escríbelo. Tu cerebro lo aprende mejor así."

"Cuando lo corran, van a ver en pantalla el nombre, la vida y el ataque de su personaje. Ya tienen la primera pieza del juego funcionando."

**[CIERRE]**

"¿Lo ven? Ya tienen datos en su programa. Ya existe un personaje. En la próxima lección le vamos a dar lógica — vamos a decidir cuándo gana, cuándo pierde, cuántos turnos tiene. El juego empieza a tomar forma."