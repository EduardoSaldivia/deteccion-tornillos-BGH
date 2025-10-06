# Detección de Tornillos BGH

Este proyecto tiene como objetivo desarrollar un sistema de inteligencia artificial para la detección automática de tornillos en productos de BGH a través de visión por computadora.

## Estructura del Repositorio

El proyecto está organizado en las siguientes carpetas para mantener el código, los datos y la documentación de manera ordenada.

```
deteccion-tornillos-BGH/
│
├── datos/                  # Contiene los datasets de imágenes.
│   ├── entrenamiento/      # Imágenes para entrenar el modelo.
│   ├── validacion/         # Imágenes para validar el rendimiento del modelo.
│   └── prueba/             # Imágenes para probar el modelo final.
│
├── modelos/                # Almacena los modelos de IA entrenados (e.g., archivos .h5, .pth).
│
├── src/                    # Código fuente principal de la aplicación.
│   ├── deteccion/          # Lógica y algoritmos de detección de objetos.
│   ├── interfaz/           # Código para las interfaces gráficas de usuario (GUI).
│   └── api/                # API para la gestión de registros (logs) y comunicación.
│
├── logs/                   # Registros y logs generados por el sistema.
│
├── config/                 # Archivos de configuración (parámetros, variables de entorno).
│
└── docs/                   # Documentación técnica, manuales y guías del proyecto.
```