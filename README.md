# Ulises y la Ola Perdida

Videojuego de plataformas y fantasía desarrollado en **GDevelop 5** para la actividad *Desarrollando un videojuego* del Taller de Programación de Videojuegos (800TP06), IPChile.

**Estudiante:** Carlos Muñoz Hasbun

Ulises, un surfista de Punta de Lobos, en Pichilemu, es arrastrado por una ola extraña hasta una isla de fantasía. Para volver a casa debe ganar una tabla de surf en la selva y la playa del primer nivel, y bajar después a un templo sumergido, donde el Caleuche escondió las runas que sostienen el mar.

## Cómo abrirlo

1. Descargar el repositorio (botón **Code**, luego **Download ZIP**) y descomprimirlo completo.
2. En GDevelop 5: **Abrir un proyecto**, luego **Mi computador**, y seleccionar `Ulises y la Ola Perdida.json`.
3. Abrir la escena `01_Menu` y presionar **Vista previa**.

Las carpetas `assets` (imágenes), `assets/audio` y `assets/video` deben quedar junto al archivo `.json`. Probado en GDevelop 5.6.

## Controles

| Tecla | Acción |
|---|---|
| Flecha izquierda y flecha derecha | Mover a Ulises |
| Espacio, Shift o flecha arriba | Saltar |
| E | Hablar con la Pincoya |
| P | Pausa |
| Enter | Avanzar en menús y diálogos |
| Espacio (en el video) | Omitir la transición |

## Qué contiene el juego

- **Mundo de fantasía en 10 pantallas:** dos niveles de cinco pantallas cada uno, con fondos continuos. El Nivel 1 transcurre en una playa al atardecer y el Nivel 2 en un templo sumergido.
- **Avatar** con comportamiento de personaje de plataformas, cuatro animaciones (11 cuadros en total) y efecto espejo.
- **3 tipos de NPC:**
  - Jaiba Centinela: patrulla entre topes invisibles y se derrota con un pisotón.
  - Lobo marino: persigue a Ulises cuando se le acerca y vuelve a su punto de origen.
  - Pincoya: personaje aliada que dialoga con la tecla E y entrega la llave del templo.
- **Interacción con el entorno:** monedas, frutas de chirimoya (vitalidad), checkpoints, pinchos de coral, llave y puerta, tabla de surf que se usa sobre el agua, y un portal que cierra cada nivel.
- **Sonido:** música en el menú y en cada nivel, ambiente en bucle por nivel, pasos distintos según la superficie (arena, madera, piedra y agua) y efectos para cada acción.
- **Estructura:** 10 escenas y 2 niveles unidos por un **video MP4** de transición.
- **Hojas de eventos** organizadas en grupos con comentarios.

## Estructura del repositorio

```
Ulises y la Ola Perdida.json   proyecto de GDevelop (10 escenas)
assets/                        51 imágenes PNG
assets/audio/                  23 sonidos y músicas OGG
assets/video/                  video de transición MP4 (H.264 y AAC)
docs/                          informe "Resolución a las orientaciones" (Word y PDF)
LEEME.txt                      resumen en texto plano
```

## Escenas

`01_Menu`, `02_Instrucciones`, `03_Intro`, `04_Nivel1`, `05_Transicion`, `06_Nivel2`, `07_Pausa`, `08_GameOver`, `09_Victoria` y `10_Creditos`.

## Informe

La resolución a las orientaciones de la actividad está en la carpeta [`docs`](docs/Resolucion_UlisesOlaPerdida.pdf).

## Recursos y uso de IA

Los gráficos, sonidos, música y el video de la transición fueron creados con apoyo de herramientas de IA. No se utilizaron recursos de repositorios externos ni de otros juegos. Las mecánicas se inspiran en *Montezuma's Revenge*, *Wonder Boy* y *Super Mario Bros.*, sin emplear material gráfico ni sonoro de esos títulos.

## Uso académico

Proyecto desarrollado como trabajo evaluado del Taller de Programación de Videojuegos de IPChile.
