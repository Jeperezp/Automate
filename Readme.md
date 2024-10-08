# Power Automate Workflows Repository

Este repositorio contiene una serie de flujos automatizados creados con **Power Automate**. Los flujos están diseñados para facilitar procesos de análisis de datos y notificaciones automatizadas. Cada flujo está documentado y preparado para ser reutilizado o modificado según las necesidades del usuario.

## 📂 Estructura del Repositorio

El repositorio está organizado en carpetas, donde cada una de ellas contiene un flujo de Power Automate independiente. Dentro de cada carpeta se incluyen los archivos `.json` necesarios para importar el flujo a Power Automate, así como un archivo **README.md** con la descripción detallada del flujo y sus funcionalidades.

- **/NotificaciónCSV**
  - Contiene un flujo para la creación y envío automatizado de archivos CSV generados a partir de un análisis de datos en Power BI.
  
- **/RPA_HelpDesk**
  - Contiene un flujo que automatiza tareas relacionadas con el procesamiento y gestión de solicitudes de soporte técnico en un entorno de Help Desk.

## 📄 Descripción General de los Flujos

### 1. **Notificación de Reporte CSV vía Correo Electrónico**
Este flujo permite generar un archivo **CSV** a partir de una acción disparada en **Power BI** y enviar dicho archivo por correo electrónico. Es ideal para analistas de datos que necesitan compartir informes o análisis de manera recurrente y automatizada.

- **Activador**: Al hacer clic en un botón en Power BI.
- **Acciones principales**:
  - Creación de tabla CSV.
  - Almacenamiento del archivo en un servicio (ej. OneDrive, SharePoint).
  - Envío del archivo CSV adjunto vía correo electrónico.
  
[Ver detalles del flujo](NotificaciónCSV/README.md)

### 2. **Automatización de Gestión en Help Desk**
Este flujo está orientado a automatizar procesos de ayuda y soporte técnico en un entorno de Help Desk. Se encarga de capturar y procesar solicitudes, así como de generar reportes o enviar notificaciones basadas en las solicitudes entrantes.

- **Activador**: Evento de soporte técnico (manual o automático).
- **Acciones principales**:
  - Procesamiento de la solicitud.
  - Gestión de respuestas automáticas.
  - Almacenamiento de registros y notificación a los equipos relevantes.
  
[Ver detalles del flujo](RPA_HelpDesk/README.md)

## 🚀 Cómo Utilizar los Flujos

### Paso 1: Clonar el Repositorio

Clona este repositorio en tu máquina local utilizando el siguiente comando:

```bash
git clone https://github.com/Jeperezp/Automate.git
