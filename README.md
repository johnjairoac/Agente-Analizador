# Agente Analizador

Automatización desarrollada en n8n para procesar y analizar facturas enviadas a través de Telegram. El sistema identifica automáticamente si el usuario envía una imagen o un documento PDF, extrae la información relevante utilizando inteligencia artificial de OpenAI y registra los datos estructurados en Google Sheets.

## Funcionalidades

* Recepción de facturas mediante Telegram.
* Procesamiento de imágenes y documentos PDF.
* Extracción automática de:

  * Tipo de comprobante.
  * Número de factura.
  * Razón social.
  * RUC o identificación fiscal.
  * Tipo de moneda.
  * Forma de pago.
  * Productos o servicios facturados.
  * Cantidades y unidades.
  * Descripciones.
  * Valores unitarios.
* Uso de Inteligencia Artificial para interpretar documentos no estructurados.
* Almacenamiento automático de la información en Google Sheets.
* Flujo completamente automatizado y escalable.

## Tecnologías utilizadas

* n8n
* Telegram Bot API
* OpenAI GPT-4o Mini
* Google Sheets API

## Casos de uso

* Digitalización de facturas.
* Automatización de procesos contables.
* Registro automático de gastos y compras.
* Integración de documentos empresariales con hojas de cálculo.
* Procesamiento inteligente de comprobantes electrónicos.

Este proyecto permite reducir significativamente el tiempo de digitación manual y mejorar la precisión en el registro de información contable y administrativa.
