# Sílabo del Curso
## Introducción a Java y la Programación Orientada a Objetos para Jóvenes

> **Universidad Peruana de Ciencias Aplicadas (UPC)**
> Carrera de Ingeniería de Software | 1ASI0729 — Desarrollo de Aplicaciones Open Source | NRC: 11881 | Período 202610
> Equipo **GreenSpot** — Líder: Rommel Hurtado Balcazar

---

## Índice de Contenidos

1. [Información General del Curso](#1-información-general-del-curso)
2. [Objetivo General del Curso](#2-objetivo-general-del-curso)
3. [Competencias y Resultados de Aprendizaje](#3-competencias-y-resultados-de-aprendizaje)
4. [Secuencia de Lecciones](#4-secuencia-de-lecciones)
5. [Metodología de Enseñanza](#5-metodología-de-enseñanza)
6. [Recursos y Herramientas](#6-recursos-y-herramientas)
7. [Evaluación y Actividades Prácticas](#7-evaluación-y-actividades-prácticas)
8. [Repositorio y Recursos Adicionales](#8-repositorio-y-recursos-adicionales)
9. [Equipo Elaborador](#9-equipo-elaborador)

---

## 1. Información General del Curso

| Campo | Detalle |
|---|---|
| **Nombre del curso** | Introducción a Java y la POO para Jóvenes |
| **Duración total** | 60 minutos |
| **Público objetivo** | Estudiantes de 12 a 17 años sin experiencia previa en programación |
| **Prerrequisitos** | Ninguno — solo disponer de un navegador web (Chrome, Firefox, Safari, Edge) |
| **Herramientas** | 100% en línea. No se requieren descargas ni instalaciones. |
| **Repositorio de código** | https://github.com/GreenSpot-app/java-fundamentals-course-greenspot |
| **Universidad** | Universidad Peruana de Ciencias Aplicadas (UPC) |
| **Carrera** | Ingeniería de Software |
| **Curso marco** | 1ASI0729 — Desarrollo de Aplicaciones Open Source |
| **NRC** | 11881 \| Período 202610 |
| **Equipo elaborador** | GreenSpot — Líder: Rommel Hurtado Balcazar |

---

## 2. Objetivo General del Curso

Al finalizar este curso de 1 hora, los estudiantes de 12 a 17 años — sin ninguna experiencia previa en programación — serán capaces de:

1. Entender qué es la programación y por qué Java es uno de los lenguajes más usados en el mundo real.
2. Comprender los conceptos fundamentales de la POO — clases y objetos — de forma visual e intuitiva, usando como hilo conductor el desarrollo de un videojuego simple.
3. Leer y escribir su primer código funcional en Java, identificando su estructura básica y lo que hace cada parte.
4. Sentir que programar es algo que ellos pueden hacer, saliendo motivados, con curiosidad encendida y sabiendo exactamente cuáles son sus próximos pasos para seguir aprendiendo.

---

## 3. Competencias y Resultados de Aprendizaje

### 3.1 Competencias Generales

- Pensamiento computacional y resolución de problemas.
- Comunicación lógica a través del código.
- Autonomía digital y motivación para el autoaprendizaje.

### 3.2 Competencias Específicas por Lección

| Lección | Resultado de Aprendizaje Esperado |
|---|---|
| **L1 — ¿Qué es Java?** | Describir qué es un programa y nombrar al menos 2 usos reales de Java. |
| **L2 — Variables** | Declarar variables de tipo `int`, `String` y `boolean` y asignarles valores correctamente. |
| **L3 — Estructuras de control** | Escribir condicionales `if-else` y bucles `for`/`while` para controlar el flujo de un programa. |
| **L4 — Métodos y E/S** | Definir y llamar métodos en Java; capturar entrada del usuario con `Scanner`. |
| **L5 — POO** | Crear una clase con atributos y métodos, instanciar objetos y usarlos en un programa funcional. |
| **L6 — Próximos pasos** | Identificar al menos 3 recursos para continuar aprendiendo Java de forma autónoma. |

---

## 4. Secuencia de Lecciones

El curso está dividido en 6 lecciones progresivas que suman 60 minutos de duración total. Cada lección incluye explicación teórica, código en vivo y una actividad práctica en línea.

| # | Título de la Lección | Tiempo | Temas Principales | Práctica |
|:---:|---|:---:|---|:---:|
| 1 | ¿Qué es Java y la Programación? | 5 min | Qué es programar, usos de Java, presentación del videojuego. | Replit |
| 2 | Variables y Tipos de Datos | 8 min | `int`, `String`, `boolean`, `double`. Variables del personaje del juego. | Replit |
| 3 | Estructuras de Control | 10 min | `if-else`, `for`, `while`. Lógica de turnos del juego. | JDoodle |
| 4 | Métodos, Entrada/Salida e Intro a POO | 12 min | Métodos, `System.out.println()`, `Scanner`, clase `Pet`. | OnlineGDB |
| 5 | Fundamentos de POO | 15 min | Clases, objetos, atributos, instanciar. Clase `Personaje` y combate. | Replit |
| 6 | Consejos y Próximos Pasos | 10 min | Repaso, recursos gratuitos, depuración, documentación Oracle. | Formulario |

### 4.1 Detalle de Cada Lección

#### Lección 1 — ¿Qué es Java y la Programación? (5 min)

**¿Qué es programar?**
Programar es darle instrucciones claras y paso a paso a una computadora para que haga algo. Las computadoras no adivinan ni interpretan: necesitan indicaciones exactas.

**¿Qué es Java?**
Java es uno de los lenguajes de programación más usados en el mundo, creado en 1995. Se usa en apps Android, sistemas bancarios, videojuegos como Minecraft, y hasta en sistemas de la NASA.

**¿Por qué aprenderlo?**
Porque te enseña a pensar con orden, hay mucha demanda laboral, y si dominas Java, aprender otros lenguajes se vuelve mucho más fácil.

**Proyecto del curso:**
Vamos a construir un videojuego de combate por turnos. Dos personajes — héroe y villano — se enfrentan hasta que uno quede sin vida. Cada lección agrega una pieza al juego.

**Primer programa:**
```java
public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("¡Hola, mundo!");
    }
}
```

> *Conclusiones clave: Java se usa para apps, juegos y más; un programa es una lista de instrucciones exactas para la computadora.*

🔗 [Ver la lección](https://youtu.be/w6tUV70jxso) | [Practicar en JDoodle](https://www.jdoodle.com/online-java-compiler) ← ¡Sin registro!

📖 **[Más información y ejemplos detallados sobre la Lección 1 →](./Lessons/L1.md)**
 
---
#### Lección 2 — Variables y Tipos de Datos (8 min)


**¿Qué es una variable?**
Una variable es como una caja con etiqueta: tiene un nombre y guarda un dato que puede cambiar. Por ejemplo, `vida = 100` guarda los puntos de vida del personaje. Si recibe daño, el valor cambia pero la caja sigue siendo la misma.

**Tipos de datos básicos:**

| Tipo | ¿Qué guarda? | Ejemplo |
|---|---|---|
| `int` | Números enteros (sin decimales) | `int vida = 100;` |
| `double` | Números con decimales | `double precio = 9.99;` |
| `String` | Texto (siempre entre comillas) | `String nombre = "Aragorn";` |
| `boolean` | Solo `true` o `false` | `boolean estaVivo = true;` |

**Variables del personaje del juego:**
```java
String nombre    = "Aragorn";
int vida         = 100;
int ataque       = 25;
boolean estaVivo = true;
```

**Mostrar en pantalla:**
```java
System.out.println("Personaje: " + nombre);
System.out.println("Vida: " + vida);
```

> *Conclusiones clave: Declara variables como `int vida = 100;` | `String` va con S mayúscula | `boolean` solo acepta `true` o `false`.*

🔗 [Ver la lección](https://youtu.be/DBz1fR87GXE) | [Practicar en JDoodle](https://www.jdoodle.com/online-java-compiler) ← ¡Sin registro!

📖 **[Más información, analogías y errores comunes de la Lección 2 →](./Lessons/L2.md)**
 
---
#### Lección 3 — Estructuras de Control (10 min)

**¿Qué es una condición?**
Una condición es una pregunta que solo tiene dos respuestas: verdadero o falso. El `if` ejecuta un bloque de código si la condición se cumple; el `else` toma el camino contrario. En el juego lo usamos para que el enemigo solo contraataque si sigue vivo, y al final para anunciar al ganador.

```java
if (vidaEnemigo > 0) {
    int danoEnemigo = ataqueEnemigo + rand.nextInt(8);
    vidaHeroe = vidaHeroe - danoEnemigo;
    System.out.println(nombreEnemigo + " contraataca por " + danoEnemigo + " puntos!");
}

if (vidaHeroe > 0) {
    System.out.println("¡VICTORIA! " + nombreHeroe + " ha ganado!");
} else {
    System.out.println("DERROTA. El " + nombreEnemigo + " fue demasiado poderoso.");
}
```

> ! No confundas `=` (asignar un valor) con `==` (comparar dos valores). `vida = 100` le da el valor 100 a vida. `vida == 100` pregunta si vida vale 100.

**¿Qué es un bucle?**
Un bucle repite un bloque de código mientras una condición sea verdadera. Sin él, tendrías que copiar el código del combate turno por turno. Con `while`, lo escribes una vez y Java lo repite solo hasta que alguien quede en 0.

```java
while (vidaHeroe > 0 && vidaEnemigo > 0) {
    int danoHeroe = ataqueHeroe + rand.nextInt(6);
    vidaEnemigo   = vidaEnemigo - danoHeroe;
    System.out.println(nombreHeroe + " ataca por " + danoHeroe + " puntos!");
    ...
    turno++;
}
```

El `&&` significa "y": ambas condiciones deben cumplirse para que el bucle continúe. El `turno++` es una forma corta de escribir `turno = turno + 1`. El daño es aleatorio gracias a `rand.nextInt(6)`, que genera un número entre 0 y 5 cada turno.

**Resumen del flujo del juego en esta lección:**

| Momento | Qué pasa |
|---|---|
| Inicio del `while` | Se verifica que ambos tengan vida |
| Turno del héroe | Ataca con daño base + aleatorio |
| `if (vidaEnemigo > 0)` | El enemigo solo contraataca si sigue vivo |
| `turno++` | Avanza al siguiente turno |
| Salida del `while` | Un `if/else` final anuncia al ganador |

> *Conclusiones clave: `while (condición) {}` repite mientras sea verdadero | `&&` combina condiciones | `turno++` incrementa en 1 | `rand.nextInt(n)` genera un número aleatorio entre 0 y n-1*

🔗 [Ver la lección](https://youtu.be/aAPqCw0Gck0) | [Practicar en JDoodle](https://jdoodle.com/execute-java-online/) ← ¡Sin registro!

📖 **[Más información, ejemplos y errores comunes de la Lección 3 →](./Lessons/L3.md)**

#### Lección 4 — Métodos, Entrada/Salida e Introducción a la POO (12 min)
**¿Qué es un método?**
Un método es un bloque de código con nombre que hace una tarea específica. Lo escribes una vez y lo llamas cuantas veces necesites. Sin métodos, tendrías que copiar la lógica de ataque en cada turno. Con métodos, solo escribes `atacar(...)` y Java sabe exactamente qué hacer.

```java
static void atacar(String atacante, String defensor,
                   int ataque, int[] vidaDefensor) {
    int dano = ataque + rand.nextInt(6);
    vidaDefensor[0] = Math.max(0, vidaDefensor[0] - dano);
    System.out.println(atacante + " ataca a " + defensor
        + " por " + dano + " puntos!");
}

static void mostrarEstado(String nombre, int vida,
                          int vidaMax, int pociones) {
    System.out.println(nombre + " | Vida: " + vida
        + "/" + vidaMax + " | Pociones: " + pociones);
}
```

Para usarlos, simplemente los llamas por su nombre en el bucle de combate:
```java
atacar(nombre, "Dragón Oscuro", ataqueHeroe, vidaEnemRef);
mostrarEstado(nombre, vidaHerRef[0], vidaMaxHeroe, pocionesRef[0]);
```

**Entrada del jugador con Scanner:**
`Scanner` es una herramienta de Java que lee lo que el jugador escribe en el teclado. Con ella el jugador elige el nombre de su personaje y su clase al inicio del juego.

```java
Scanner scanner = new Scanner(System.in);

System.out.print("¿Cómo se llama tu personaje? ");
String nombre = scanner.nextLine();

System.out.println("Elige tu clase:");
System.out.println("  1. Guerrero — 120 vida | 18 ataque | 3 pociones");
System.out.println("  2. Mago     —  80 vida | 22 ataque | 2 pociones");
String clase = scanner.nextLine();

if (clase.equals("2")) {
    vidaHeroe   = 80;
    ataqueHeroe = 22;
} else {
    vidaHeroe   = 120;
    ataqueHeroe = 18;
}
```

> ! Para comparar Strings en Java nunca uses `==`. Usa siempre `.equals()`: `clase.equals("2")` en vez de `clase == "2"`.

**Primera mirada a la POO:**
Por ahora el héroe son variables sueltas: `vidaHeroe`, `ataqueHeroe`, `pociones`. En la Lección 5 agruparemos todo eso dentro de una clase `Personaje`. El código hará exactamente lo mismo, pero mucho más ordenado.

```java
class Personaje {
    String nombre;
    int vida;
    int ataque;
    int pociones;
}
```

**Métodos creados en esta lección:**

| Método | ¿Qué hace? |
|---|---|
| `atacar(...)` | Calcula el daño y lo aplica al defensor |
| `mostrarEstado(...)` | Imprime vida, vida máxima y pociones |
| `usarPocion(...)` | Cura 30 de vida si quedan pociones disponibles |

> *Conclusiones clave: `static void atacar(...) {}` define un método | `scanner.nextLine()` lee lo que escribe el jugador | `.equals()` para comparar Strings | `class Personaje {}` es el primer paso hacia la POO*

🔗 [Ver la lección](https://www.youtube.com/watch?v=UMF17QsrqZk) | [Practicar en OnlineGDB](https://onlinegdb.com/your-gdb-id) ← ¡Sin registro!

📖 **[Más información, ejemplos y errores comunes de la Lección 4 →](./Lessons/L4.md)**

## Lección 5 — Fundamentos de POO y el Juego Completo *(15 min)*

---

## ¿Qué es una clase y qué es un objeto?

Piensen en un molde de galletas. El molde define la forma y el tamaño, pero no es una galleta. Las galletas son lo que produces con ese molde.

- **La Clase (El Molde):** Es la plantilla llamada `Personaje`. Define que todo personaje tiene `nombre`, `vida`, `ataque` y `pociones`.
- **El Objeto (La Galleta):** Es la creación real. Creamos el `heroe` y el `enemigo`. Cada uno tiene sus propios valores, pero siguen el mismo molde.

---

## Atributos y métodos dentro de una clase

Una clase organiza el código en dos partes fundamentales:

- **Atributos:** Las características (datos). Ej: `nombre`, `vida`, `ataque`.
- **Métodos:** Las acciones (lo que puede hacer). Ej: `atacar()`, `mostrarEstado()`, `usarPocion()`.

---

## Crear nuestra primera clase: `Personaje`

El **constructor** es un método especial que inicializa los valores al crear el objeto. La palabra `this` permite que el objeto se refiera a sí mismo.

```java
abstract class Personaje {
    private String nombre;
    private int vida, vidaMaxima, ataque, pociones;

    Personaje(String nombre, int vida, int ataque, int pociones) {
        this.nombre    = nombre;
        this.vida      = vida;
        this.vidaMaxima = vida;
        this.ataque    = ataque;
        this.pociones  = pociones;
    }

    public abstract void atacar(Personaje enemigo);
}
```

---

## Instanciar objetos y usarlos

Con la palabra `new` le decimos a Java que reserve espacio en memoria y cree un objeto real usando el molde.

```java
Personaje heroe   = new Guerrero(nombre);
Personaje enemigo = new DragonOscuro();
```

---

## Métodos clave creados

| Método | ¿Qué hace? |
|---|---|
| `atacar(Personaje e)` | Lógica de combate que aplica daño al enemigo. |
| `usarPocion()` | Método concreto que restaura vida y gestiona inventario. |
| `mostrarEstado()` | Imprime los datos actuales del objeto. |

---

## Conclusiones clave

- **Clase** es el molde → **Objeto** es la creación
- `private` encapsula los datos
- `extends` aplica herencia
- `abstract` define métodos obligatorios
- `@Override` permite polimorfismo
> 🔗 [Ver la lección](https://www.youtube.com/watch?v=oDlQt8go1Qo) | [Proyecto final en Replit](https://replit.com/@your-final-java) ← ¡Guarda y comparte!

## Lección 6 — Consejos y Próximos Pasos *(10 min)*

---

## Resumen de lo aprendido

Has construido un juego completo desde cero. Dominaste:

1. **Variables y Estructuras:** Guardar datos y controlar el flujo (`if/else`, `while`).
2. **Organización:** Uso de métodos para limpiar el código.
3. **POO Profesional:** Encapsulamiento, Abstracción, Herencia, Polimorfismo e Interfaces.

---

## ¿Qué sigue después de este curso?

- **Profundiza en Java:** Aprende colecciones (`ArrayList`), manejo de excepciones (`try-catch`) y concurrencia.
- **Explora nuevos horizontes:** Android, Spring Boot o Inteligencia Artificial con Python.

---

## Recursos gratuitos recomendados

| Recurso | Descripción |
|---|---|
| **Oracle Java Tutorials** | La documentación oficial, la fuente más fiable. |
| **Codecademy** | Curso interactivo directamente en el navegador. |
| **CS50 de Harvard** | El mejor curso introductorio a la computación del mundo. |
| **YouTube** | Canales como *Programación ATS* o *MoureDev*. |

---

## Mensaje final

> La programación no es para genios, es para personas curiosas que no se rinden.
> Hoy diste el primer paso. **¡No lo dejes aquí!**

---

## Conclusiones clave

- Depurar errores es aprender
- La curiosidad supera al talento
- Mantén tu proyecto en GitHub
- ¡Sigue construyendo!
> 🔗 [Ver la lección](https://www.youtube.com/watch?v=Dk6IU8W7Hh0) | [Compartir tu trabajo](https://forms.gle/your-form)

---

## 5. Metodología de Enseñanza

El curso emplea un enfoque de aprendizaje activo y basado en proyectos:

- **Aprendizaje basado en proyectos (ABP):** cada concepto se construye en el contexto de un videojuego de RPG por turnos.
- **Progresión incremental:** cada lección agrega una capa de complejidad sobre la anterior, de modo que el estudiante siempre tiene algo que funciona.
- **Herramientas sin instalación:** todas las actividades prácticas se realizan en entornos en línea (Replit, JDoodle, OnlineGDB) para eliminar barreras técnicas.
- **Sin registro obligatorio:** la mayoría de actividades están marcadas como de acceso inmediato para reducir la fricción de entrada.
- **Motivación intrínseca:** el hilo conductor del videojuego proporciona un contexto lúdico que mantiene la curiosidad activa.

---

## 6. Recursos y Herramientas

### 6.1 Plataformas de Práctica en Línea

| Plataforma  | Uso en el Curso                                       | Registro |
|-------------|-------------------------------------------------------|---|
| **JDoodle**| Todas las lecciones estan brindadas en la herramienta | No requerido — inicio inmediato |

### 6.2 Tabla de Actividades por Lección

| Lección | Actividad | Enlace                                                    |
|:---:|---|-----------------------------------------------------------|
| 1 | Hola Mundo en Java | [JDoodle](https://www.jdoodle.com/online-java-compiler)    |
| 2 | Variables del personaje | [JDoodle](https://www.jdoodle.com/online-java-compiler)    |
| 3 | Bucles y condiciones | [JDoodle](https://www.jdoodle.com/online-java-compiler)   |
| 4 | Métodos y entrada del usuario | [JDoodle](https://www.jdoodle.com/online-java-compiler) |
| 5 | Programa POO — Clase Personaje | [JDoodle](https://www.jdoodle.com/online-java-compiler)    |

### 6.3 Repositorio de Código

Todo el código fuente del curso está disponible públicamente en GitHub:
🔗 https://github.com/GreenSpot-app/java-fundamentals-course-greenspot

---

## 7. Evaluación y Actividades Prácticas

Cada lección tiene asociada una actividad práctica en línea. La participación es autoguiada; no hay calificación formal. Al finalizar el curso, el estudiante puede compartir su proyecto completado.

| Lección | Actividad | Plataforma | Nota |
|:---:|---|---|---|
| 1 | Hola Mundo en Java | JDoodle | Sin registro |
| 2 | Variables del personaje | JDoodle | Sin registro |
| 3 | Bucles y condiciones | JDoodle | Sin registro |
| 4 | Métodos y entrada del usuario | JDoodle | Sin registro |
| 5 | Programa POO — Clase Personaje | JDoodle | Opcional (guardar/compartir) |
| Final | Cuestionario de conocimientos | Google Forms | Enlace en el README |

🔗 [Cuestionario de conocimientos](https://forms.gle/Y65vT5cvHFw1QdYq7) | Comparte tu trabajo con **#JavaBeginners**

---

## 8. Repositorio y Recursos Adicionales

### 8.1 Código Fuente

Todo el código desarrollado durante el curso está disponible en el repositorio oficial del equipo GreenSpot:
🔗 https://github.com/GreenSpot-app/java-fundamentals-course-greenspot

### 8.2 Recursos para Seguir Aprendiendo

- **Oracle Java Documentation** — docs.oracle.com/en/java/ — Referencia oficial del lenguaje.
- **Codecademy Learn Java** — Curso interactivo gratuito en línea.
- **CS50's Introduction to Programming** — Harvard OpenCourseWare.
- **Canal de YouTube «Programación ATS»** — Videos en español sobre Java desde cero.
- **Libro gratuito «Think Java»** (Downey & Mayfield) — greenteapress.com.

### 8.3 Hashtag de la Comunidad

Comparte tu proyecto final usando **#JavaBeginners**

---

## 9. Equipo Elaborador

| Campo | Detalle                                           |
|---|---------------------------------------------------|
| **Universidad** | Universidad Peruana de Ciencias Aplicadas (UPC)   |
| **Carrera** | Ingeniería de Software                            |
| **Curso** | 1ASI0729 — Desarrollo de Aplicaciones Open Source |
| **NRC** | 11881                                             |
| **Período** | 202610                                            |
| **Nombre del equipo** | GreenSpot                                         |
| **Líder del equipo** | Rommel Hurtado Balcazar                           |
| **Integrantes** | Rommel Hurtado Balcazar \ Mathias Acuache \ Kiara |
| **Fecha de entrega** | [Fecha de entrega]                                |

---

*¡Gracias por completar el curso! — GreenSpot © UPC 202610*
