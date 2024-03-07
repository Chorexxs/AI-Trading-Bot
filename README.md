# Bot de Trading

## Disclaimer

**Nota:** Este proyecto se ha creado únicamente con fines educativos. No está destinado para operar en el mundo real con fondos reales. El bot de trading proporcionado es una demostración y debería utilizarse solo en un entorno simulado o en papel.

## Descripción general

Este repositorio contiene un bot de trading implementado en Python utilizando la biblioteca LumiBot. El bot utiliza análisis de sentimiento en noticias financieras para tomar decisiones de trading en un entorno simulado.

## Instalación

1. Instalar dependencias:

   ```bash
   pip install lumibot alpaca-trade-api transformers torch
   ```

2. Obtener claves de API de Alpaca:

   - Regístrate para obtener una cuenta de trading simulada en [Alpaca](https://app.alpaca.markets/signup)
   - Obtén la clave API y el secreto desde el panel de Alpaca

3. Actualizar credenciales de API:

   - Abre el archivo `main.py`
   - Reemplaza `API_KEY` y `API_SECRET` con tus credenciales de API de Alpaca

## Uso

1. Ejecutar el bot de trading:

   ```bash
   python main.py
   ```

2. Monitorear la salida en la consola para obtener información sobre el bot y ver la gráfica en el navegador web

## Derechos

Proyecto hecho siguiendo el tutorial de Nicholas Renotte en [YouTube](https://www.youtube.com/watch?v=c9OjEThuJjY)

Ninguno de los derechos me pertenece.
