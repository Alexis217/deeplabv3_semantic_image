# DeepLab - Segmentación Semántica con Cámara

Este proyecto es una aplicación web que utiliza modelos pre-entrenados de DeepLab para realizar **segmentación semántica** en tiempo real usando la cámara de tu dispositivo. Permite seleccionar entre tres modelos diferentes: Pascal, Cityscapes y ADE20K.

## ¿Qué es la segmentación semántica?

La segmentación semántica es una técnica de visión por computadora que asigna una etiqueta de clase a cada píxel de una imagen, permitiendo identificar objetos y regiones dentro de una escena.

## ¿Cómo funciona la aplicación?

1. **Captura de imagen:** Utiliza la cámara web para capturar una imagen.
2. **Selección de modelo:** Puedes elegir entre tres modelos de segmentación (Pascal, Cityscapes, ADE20K).
3. **Procesamiento:** El modelo seleccionado procesa la imagen y genera un mapa de segmentación.
4. **Visualización:** Se muestra el resultado en un canvas junto con una leyenda de colores para cada clase detectada.

## Archivos principales

- **index.html:** Estructura de la página web, incluye los botones, el video de la cámara y los contenedores para los resultados.
- **style.css:** Estilos visuales para la interfaz.
- **script.js:** Lógica principal de la aplicación. Gestiona la cámara, la carga y ejecución de los modelos, y la visualización de resultados.

## Requisitos

- Navegador moderno con soporte para JavaScript y acceso a la cámara.
- Conexión a internet para cargar los modelos de TensorFlow.js.

## Instrucciones de uso

1. Abre `index.html` en tu navegador.
2. Permite el acceso a la cámara cuando el navegador lo solicite.
3. Haz clic en uno de los botones de modelo para realizar la segmentación.
4. Observa el resultado y la leyenda de clases segmentadas.

## Créditos

- [TensorFlow.js DeepLab Model](https://github.com/tensorflow/tfjs-models/tree/master/deeplab)
- Inspirado en ejemplos de segmentación semántica en tiempo real.

---

