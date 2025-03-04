# n8n Workflow: Envío de correos personalizados desde Excel

Este flujo de trabajo de n8n permite enviar correos electrónicos personalizados a partir de una tabla de Excel.

## Requisitos
1. **n8n**: Asegúrate de tener n8n instalado y en funcionamiento.
2. **Archivo Excel**: El archivo debe tener columnas como `Nombre`, `Edad`, `Email`, etc.
3. **Credenciales de correo**: Necesitarás credenciales de un servicio de correo (Gmail, SMTP, etc.).
4. **Credenciales de Google Sheets**: Necesitarás credenciales de google Sheets o puedes usar las mias ya dentro del Workflow para probar

## Instrucciones
1. Clona este repositorio.
2. Importa el archivo `workflow.json` en n8n.
3. Configura las credenciales de correo electrónico y google sheets en n8n
4. Carga el archivo `emails_prueba.xlsx` o reemplázalo con tu propio archivo Excel en tu google sheets(Deben ser Emails reales para que se pueda comprobar que funciona).
5. Ejecuta el flujo de trabajo.
   

## Estructura del archivo Excel
El archivo Excel debe tener las siguientes columnas:
- `Nombre`: Nombre del destinatario.
- `Edad`: Edad del destinatario.
- `Email`: Correo electrónico del destinatario.

## Créditos
Este flujo de trabajo fue creado por David Mazorra.
