# 22354 — Programación Avanzada · UIB

Material docente de la asignatura **22354 — Programación Avanzada**, obligatoria de segundo curso
del [Grado en Ingeniería Telemática](https://estudis.uib.es/estudis-de-grau/grau/telematica/GTT2-P/)
de la [Escola Politècnica Superior](https://eps.uib.es/) de la
[Universitat de les Illes Balears](https://www.uib.es).

### 🌐 [uib-22354-programacion-avanzada.github.io/website](https://uib-22354-programacion-avanzada.github.io/website/)

Ahí está todo: un resumen de la guía docente, horario/calendario, el material teórico de los cinco temas, los ejercicios, la
bibliografía y los recursos de apoyo. Los repositorios de esta organización contienen el **código**
que acompaña a ese material.

## Qué hay aquí

| Repositorio | Qué es |
|---|---|
| **`website`** | El sitio de la asignatura, escrito en [Quarto](https://quarto.org/) |
| **`tN-ejemplos`** | Todo el código del tema *N*, compilable y con sus pruebas, para ejecutar y experimentar |
| **`tN-ejercicios`** | El esqueleto de los ejercicios del tema *N*: las firmas están, los cuerpos los pones tú |

Los dos últimos son **repositorios plantilla**: pulsa *Use this template* para crear tu copia y
trabajar en ella. Vienen preparados para abrirse en **GitHub Codespaces**, así que puedes empezar
sin instalar nada en tu ordenador.

## Cómo empezar

1. Entra en `t1-ejemplos` y pulsa **Use this template → Create a new repository** en tu cuenta.
2. En tu copia, **Code → Codespaces → Create codespace on main**. La primera vez tarda unos
   minutos.
3. En el terminal: `mvn test`. Si termina en verde, ya tienes el entorno completo.
4. Repite con `t1-ejercicios`. Ahí, al contrario, casi todas las pruebas deben **fallar**: eso es
   lo que vas a arreglar.

Necesitas una cuenta de GitHub (gratuita). Si prefieres trabajar en tu ordenador, el `README.md`
de cada repositorio explica cómo hacerlo con IntelliJ IDEA Community y JDK 25.

> **Acuérdate de detener el Codespace** cuando termines (*Code → Codespaces → ⋯ → Stop codespace*):
> mientras está encendido consume tu cuota mensual gratuita.

## La asignatura

Cinco temas, 60 horas presenciales:

| # | Tema | Horas |
|---|---|:---:|
| 1 | POO, principios SOLID y diseño | 12 |
| 2 | Algoritmos, complejidad y estructuras de datos | 8 |
| 3 | Programación concurrente | 16 |
| 4 | Programación de red y servicios distribuidos | 12 |
| 5 | Bases de datos: SQL, JDBC y NoSQL | 12 |

La pila es **Java 25**, **Maven**, **JUnit 5**, **GitHub Codespaces** y **GitHub Actions**. Un
mismo ejemplo recorre el curso entero —un monitor de servicios de red— y va ganando concurrencia,
comunicación por sockets y persistencia a medida que avanzan los temas: al terminar habrás
construido el sistema completo, pieza a pieza.

El hilo metodológico transversal es el **uso responsable de los copilotos de IA**, articulado como
*especificar → generar → verificar*. Las condiciones concretas están en la
[guía docente](https://uib-22354-programacion-avanzada.github.io/website/es/informaciones/guia-docente.html):
en resumen, puedes pedir explicaciones y revisión, pero entregar código que no sabes explicar,
justificar ni modificar se considera uso indebido.

## Licencia

El material docente se publica bajo
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en) y el código de los
ejemplos y ejercicios bajo licencia **MIT**. Puedes reutilizarlo en tu docencia citando la fuente.

## Contacto

Alejandro Mesejo — [alejandro.mesejo@uib.es](mailto:alejandro.mesejo@uib.es)
Despacho 186, edificio Anselm Turmeda, UIB.
