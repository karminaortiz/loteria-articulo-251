# Lotería Fiscal — Artículo 251 LSS

Incluye:
- 50 tableros diferentes de 3×3.
- 12 tarjetas/pistas basadas en la presentación.
- Modo Jugador para celular.
- Modo Cantador.
- Sala en línea con PeerJS para que el cantador envíe la pista a los celulares.
- Marcado de casillas y validación de “¡Lotería!”.
- Guardado local del tablero y nombre.

## Cómo usarla
1. Sube `index.html` a un servicio que permita HTTPS, por ejemplo GitHub Pages o Netlify.
2. Abre la página.
3. En un celular/computadora elige “Cantador” → “Crear sala”.
4. Comparte el código de sala.
5. Los demás entran a “Jugador”, eligen tablero 1–50 y escriben el código.
6. El cantador usa “Siguiente pista”.

Nota: PeerJS necesita internet y una página servida por HTTPS para la conexión entre dispositivos.
