# Dileycita 🧜‍♀️

Un juego submarino de "come o serás comida". Controla a la sirena Dileycita, cómete
los peces más pequeños para crecer y esquiva a los más grandes.

- **Móvil:** arrastra con el dedo (juega en horizontal / landscape)
- **Ordenador:** flechas ← ↑ ↓ →

## Power-ups
- 🥩 **Picanha** — MODO GLOTÓN: cómete todos los peces durante 7s (¡y al tiburón!)
- 🧪 **Brujería** — hechiza a todos los peces, nadan lento 4s
- 🍹 **Caipirinha** — te marea: cuesta nadar 4s (trampa)

🦈 Cada ~1 minuto llega un **tiburón**: el agua tiembla como aviso y los peces huyen.
El tiburón siempre te mata... salvo si tienes la **picanha** activa, ¡entonces te lo comes!

HTML5 + canvas puro, sin build. Abre `index.html` o juega la versión publicada.

## Archivos
- `index.html` — el juego completo
- `frames/` — el sprite animado de la jugadora (fotogramas de un vídeo, fondo recortado)
- `picanha.png` / `brujeria.png` / `caipirinha.png` — los power-ups
- `dileycita.mp3` — la música de fondo
- `cutout.swift` / `cutout_batch.swift` — scripts de Vision que recortan el fondo por fotograma
