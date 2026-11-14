# Aguitech Arcade

Diez minijuegos de movimiento para activaciones. Abre el menú y elige una experiencia. Cada partida dura de 15 a 180 segundos y guarda su récord local.

```bash
python3 -m http.server 8000
```

Abre http://localhost:8000. En un servidor remoto, usa HTTPS para activar la cámara. El control con puntero, pantalla táctil o flechas y Espacio funciona sin cámara. La cámara requiere conexión para descargar MediaPipe y su modelo. La detección corre en el navegador y el juego no envía ni guarda el video.

Esta primera versión usa seguimiento de una persona. Los retos de ritmo y sombra usan ambas manos y el robot combina la posición del torso con un gesto de mano.
