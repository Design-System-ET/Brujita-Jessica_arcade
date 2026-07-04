# Brujita Arcade

Brujita Arcade es un juego web tipo arcade creado con HTML, CSS y JavaScript vanilla. El jugador controla a Brujita en una aventura de reparto nocturno, recoge pociones, las entrega a los clientes y esquiva enemigos mientras avanza por varios niveles.

## Características

- Juego de arcade en navegador con canvas
- Controles por teclado y pantalla táctil
- Joystick virtual y botón de acción para móviles
- HUD con puntuación, nivel, vidas y combo
- Pantallas de inicio, victoria, game over y avance de nivel
- Música y efectos de sonido en la carpeta de audio
- Diseño responsive con temática mágica y nocturna

## Requisitos

Solo necesitas un navegador moderno con soporte para HTML5, Canvas y JavaScript.

## Cómo ejecutar el proyecto

Opción sencilla:
1. Abre [index.html](index.html) directamente en tu navegador.

Opción recomendada para evitar problemas con archivos de audio:
1. Abre una terminal en la carpeta del proyecto.
2. Ejecuta un servidor local, por ejemplo: `python -m http.server 8000`
3. Visita `http://localhost:8000` en tu navegador.

## Controles

- Movimiento: WASD o flechas del teclado
- Disparo: Espacio
- Móvil: joystick virtual para moverse y botón de acción para disparar

## Estructura del proyecto

- [index.html](index.html): estructura principal de la página, canvas, HUD y overlays
- [styles.css](styles.css): estilos visuales, diseño responsive y controles táctiles
- [script.js](script.js): lógica del juego, bucle principal, input, entidades, colisiones y renderizado
- [audio/](audio/): música, narración y efectos de sonido del juego
- [.gitignore](.gitignore): archivos y carpetas ignorados por Git
- [LICENSE](LICENSE): licencia del proyecto
- [extensions-list.txt](extensions-list.txt): lista de extensiones recomendadas para el entorno de desarrollo
- [canvas-debug.png](canvas-debug.png): captura de depuración del canvas

## Desarrollo

El proyecto está pensado como un prototipo de juego arcade web simple y fácil de extender. Puedes modificar:
- los niveles en la sección `LEVELS` de [script.js](script.js)
- la apariencia en [styles.css](styles.css)
- la estructura del menú y HUD en [index.html](index.html)

## Licencia

Este proyecto está bajo la licencia MIT. Consulta [LICENSE](LICENSE) para más detalles.
