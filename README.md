# Adivina la palabra (el ahorcado) — ejercicio 23

Juego del ahorcado en el navegador. El repo se llama “react”, pero el código de este ejercicio es **HTML + JavaScript** (sin React).

## Qué hace

- Elige una palabra al azar de la lista en `palabras.js`
- Muestra huecos `_` y un teclado en pantalla
- Si fallas, se van revelando partes del dibujo SVG
- Diálogo de ganado / perdido y opción de volver a empezar

## Cómo probarlo

No hace falta instalar nada. Abre `index.html` en el navegador, o sirve la carpeta con cualquier servidor estático.

Demo: https://react-23-palabras.netlify.app

## Cómo lo construí

- `index.html`: marcado, estilos con Tailwind por CDN, SVG del ahorcado y la lógica del juego
- `palabras.js`: array de palabras (`PALABRAS`)
- DOM a mano: teclado con `createElement`, estado en variables (`error`, `palabraAdivinada`, etc.)

## Cómo comprobarlo

Sin tests. Abro la demo o el HTML, juego una partida ganando y otra perdiendo, y miro que el dibujo y el mensaje final cuadren.

---

Moussi Joelle · [github.com/moussijoelle](https://github.com/moussijoelle)
