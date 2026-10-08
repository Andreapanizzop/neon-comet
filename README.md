# ☄️ NEON COMET — Cosmic Survival

Arcade cósmica de supervivencia creada con HTML5 Canvas, CSS y JavaScript vanilla. No necesita instalación ni librerías.

## Jugar
Cuando GitHub Pages esté activado, la demo estará en:
https://Andreapanizzop.github.io/neon-comet/

## Controles
- **Mover la nave:** WASD o flechas del teclado.
- **Móvil:** toca y arrastra en el área de juego.
- **Pausa:** tecla P o botón Pausar.
- **Objetivo:** esquiva asteroides, recoge núcleos cian y sobrevive.
- Cada núcleo da 100 puntos base; recoger varios seguidos activa un combo multiplicador.
- Cada 1.000 puntos aumenta el sector y la dificultad.
- El récord se guarda en el navegador con localStorage.
- El sonido se genera con Web Audio API y se puede silenciar.

## Ejecutar localmente
Abre `index.html` en un navegador moderno o inicia un servidor estático:
```bash
python3 -m http.server 8000
```
Visita http://localhost:8000.

## Activar GitHub Pages
1. En el repositorio abre **Settings → Pages**.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Elige la rama `main` y la carpeta `/(root)`, y guarda.
4. Espera a que termine el workflow de Pages. URL: https://Andreapanizzop.github.io/neon-comet/

## Archivos
- `index.html`: estructura, HUD y pantallas de inicio/fin.
- `styles.css`: diseño neón adaptable a móvil y escritorio.
- `script.js`: mecánicas, renderizado, puntuación, colisiones y audio.
