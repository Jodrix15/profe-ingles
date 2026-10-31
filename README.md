# Profe de inglés

Fichas interactivas de inglés para mis clases particulares: examen de nivel, ejercicios, teoría y vocabulario. Se puede instalar en el móvil como una app.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white)

🌐 **Web:** https://jodrix15.github.io/profe-ingles/

## Contenido

| Sección | Página | Qué es |
|---|---|---|
| Examen | `examen-nivel.html` | 30 preguntas para saber el nivel del alumno (A1–B1) |
| Fichas | `ficha-ingles.html` | Ficha 1: pronombres, posesivos y *do* |
| Fichas | `ficha-2.html` | Ficha 2: *be* y presente, con frases de tienda y de viaje |
| Teoría | `teoria-1.html` | Lo necesario para resolver la ficha 1 |
| Teoría | `teoria-2.html` | Unidades 1–7: *to be*, presente continuo y presente simple |
| Vocabulario | `vocabulario.html` | Flashcards de tienda, ropa, viajes y verbos |

## Instalar en el móvil

Abre la web en el móvil y elige **Añadir a la pantalla de inicio**. Funciona como una app gracias a `manifest.webmanifest` y al service worker (`sw.js`).

> [!TIP]
> Si después de un cambio no se ve la versión nueva, pulsa **↻ Actualizar** en la portada.

## Añadir una ficha nueva

1. Crea el archivo HTML de la ficha.
2. Añade su enlace en `index.html`, en la sección que le toque.
3. Añádelo a la lista `FILES` de `sw.js` y sube el número de `CACHE` (`fichas-v8` → `fichas-v9`) para que funcione sin conexión y se actualice.
4. Haz commit y push a `main`.

---

🤖 Desarrollado con ayuda de [Claude](https://claude.ai) como asistente de programación.
