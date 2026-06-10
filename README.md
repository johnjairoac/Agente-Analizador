# 🤖 Agente Analizador

![n8n](https://img.shields.io/badge/n8n-Workflow-orange)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-green)
![Telegram](https://img.shields.io/badge/Telegram-Bot-blue)
![Google Sheets](https://img.shields.io/badge/Google-Sheets-success)

## 📋 Descripción

Automatización desarrollada en **n8n** para procesar y analizar facturas enviadas a través de **Telegram**. El sistema identifica automáticamente si el usuario envía una imagen o un documento PDF, extrae la información relevante utilizando inteligencia artificial de **OpenAI** y registra los datos estructurados en **Google Sheets**.

---

## 🏗️ Arquitectura

```text
📱 Telegram
      │
      ▼
🤖 OpenAI GPT-4o
      │
      ▼
📊 Extracción de Datos
      │
      ▼
📈 Google Sheets
```

---

## 🚀 Funcionalidades

### 📲 Recepción de Facturas

* Recepción automática mediante Telegram.
* Soporte para imágenes y documentos PDF.

### 🧠 Extracción Inteligente

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

### 📊 Almacenamiento Automático

* Registro automático en Google Sheets.
* Información estructurada y lista para análisis.

### ⚡ Automatización Completa

* Flujo totalmente automatizado.
* Escalable para múltiples usuarios y empresas.

---

## 🛠️ Tecnologías Utilizadas

| Tecnología            | Uso                     |
| --------------------- | ----------------------- |
| 🤖 n8n                | Automatización          |
| 📱 Telegram Bot API   | Recepción de documentos |
| 🧠 OpenAI GPT-4o Mini | Extracción inteligente  |
| 📊 Google Sheets API  | Almacenamiento de datos |

---

## 💼 Casos de Uso

* 📄 Digitalización de facturas.
* 💰 Automatización de procesos contables.
* 🧾 Registro automático de gastos y compras.
* 📊 Integración con hojas de cálculo.
* 🤖 Procesamiento inteligente de comprobantes electrónicos.

---

## 📈 Beneficios

✅ Reducción del tiempo de digitación manual.

✅ Mayor precisión en el registro de información.

✅ Centralización automática de documentos.

✅ Escalabilidad para procesos empresariales.

---

## 📥 Instalación

1. Descargar el archivo JSON del workflow.
2. Importarlo en n8n.
3. Configurar las credenciales de Telegram.
4. Configurar las credenciales de OpenAI.
5. Configurar Google Sheets.
6. Activar el workflow.

---

