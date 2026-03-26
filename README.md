# Start-up Guía Turística basada en IA
Este trabajo consiste en un asistente turístico inteligente y multimodal basado en Inteligencia Artificial. El objetivo es, a partir de la implementación de sistemas multimodales y uso de modelos de Inteligencia Artificial, conseguir un modelo que permita al usuario obtener información (a través de texto, audio o imágenes) sobre el destino al que viaje. 

## Estructura del repositorio

```text
├── guIA_turistica.ipynb            # Notebook principal que se podrá ejecutar en local
├── guIA_turistica_colab.ipynb      # Notebook diseñado para poder usarse en Google Colab
├── historiales/                    # Carpeta autogenerada con los registros de viaje (.txt)
├── imagenes/                       # Carpeta sugerida para las fotos de monumentos/textos
├── README.md                       # Documentación del proyecto
├── requirements.txt                # Documento donde aparecen las instrucciones para que pueda ejecutarse guIA_turistica.ipynb
└── guia_turistica.yml              # Entorno necesario para ejecutar guIA_turistica.ipynb

Una vez ejecutado `await start_up()` se podrá navegar por un menú formado por diferentes opciones para obtener información sobre el lugar al que vas a viajar (se podrá escribir, subir un audio, o hablar sobre tu duda) y generar una respuesta por texto que también podrá ser escuchada. La subida de imágenes será útil para identificar e obtener información sobre el monumento que aparezca en la foto o traducir texto mostrado en la imagen. También, se podrá generar un historial de las respuestas obtenidas en cada viaje.

