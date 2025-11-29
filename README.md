# LabTrack AI

Sistema de seguimiento de muestras para laboratorios con códigos de barras e inteligencia artificial.

Desarrollado para **SAFER Agrobiológicos** - Colombia.

## 🚀 Demo en Vivo

- **Dashboard Principal:** [Abrir Dashboard](https://TUUSUARIO.github.io/labtrack-ai/)
- **Generador de Códigos:** [Abrir Generador](https://TUUSUARIO.github.io/labtrack-ai/barcode-generator.html)

## ✨ Características

- 📊 **Dashboard en tiempo real** - Vista general de todas las muestras
- 🏷️ **Generador de códigos de barras** - Code128 compatible con impresoras térmicas
- 📷 **Escáner de códigos** - Usa la cámara del celular para buscar muestras
- 🔍 **Búsqueda instantánea** - Encuentra cualquier muestra por código
- 📝 **Actualización de estado** - Cambia el estado de las muestras con un clic
- 🤖 **Asistente IA** - Consulta datos en español con lenguaje natural

## 📱 Capturas de Pantalla

### Dashboard
![Dashboard](screenshots/dashboard.png)

### Escáner Móvil
![Scanner](screenshots/scanner.png)

### Generador de Etiquetas
![Barcode](screenshots/barcode.png)

## 🛠️ Tecnologías

- **Frontend:** HTML5, CSS3, JavaScript
- **Base de datos:** Airtable
- **API:** Make.com (Webhooks)
- **IA:** OpenAI GPT (Custom GPT)
- **Códigos de barras:** JsBarcode, Html5-QRCode

## 📋 Estructura del Sistema

```
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│  Formulario de  │────▶│    Airtable     │────▶│   Make.com API  │
│     Ingreso     │     │   (Database)    │     │   (Webhook)     │
└─────────────────┘     └─────────────────┘     └────────┬────────┘
                                                         │
                        ┌────────────────────────────────┼────────────────────────────────┐
                        │                                │                                │
                        ▼                                ▼                                ▼
               ┌─────────────────┐             ┌─────────────────┐             ┌─────────────────┐
               │    Dashboard    │             │   GPT Assistant │             │  Barcode Tools  │
               │   (Web App)     │             │  (Natural Lang) │             │ (Gen + Scanner) │
               └─────────────────┘             └─────────────────┘             └─────────────────┘
```

## 🚀 Instalación

1. Clona este repositorio
2. Configura tu webhook URL en los archivos HTML
3. Despliega en GitHub Pages o cualquier hosting estático

## 👨‍💻 Desarrollado por

**Issouf** - AI Operations Consulting

## 📄 Licencia

Propietario - SAFER Agrobiológicos © 2025
