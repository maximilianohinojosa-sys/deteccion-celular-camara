# Detector de celulares con cámara

Página web que detecta teléfonos móviles en vivo usando la cámara del equipo.

- **IA:** COCO-SSD (clase `cell phone`) sobre TensorFlow.js, en el navegador.
- **Privacidad:** el video se procesa localmente; no se envía ni se guarda.
- **Sin instalación:** un solo `index.html`. Para probar en local: `python3 -m http.server` y abrir `http://localhost:8000`.
- **Requiere** HTTPS o localhost para acceder a la cámara.

## Límites
Es una demo con un modelo general (COCO): puede fallar con celulares pequeños, lejanos, de lado o parcialmente tapados, y confundirlos con otros objetos. No identifica personas ni modelos.
