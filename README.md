# Agente IA

Este repositorio contiene un agente de inteligencia artificial diseñado para integrarse y automatizar flujos de trabajo mediante **n8n**, una plataforma de automatización de código abierto.

## Requisitos Previos

1. **Plataforma n8n:**
   - Asegúrate de tener una instancia de n8n en funcionamiento. Puedes instalarla localmente, en un servidor o usar la versión en la nube.

2. **Node.js**
   - Versión recomendada: `>=16.0.0`

3. **Dependencias adicionales:**
   - Este proyecto utiliza varias dependencias que están listadas en el archivo `package.json`. Asegúrate de instalar estas dependencias ejecutando:

     ```bash
     npm install
     ```

## Configuración

### Paso 1: Clonar el Repositorio

Clona este repositorio en tu máquina local:

```bash
git clone https://github.com/lepc1972/agente-ia.git
cd agente-ia
```

### Paso 2: Configurar las Credenciales en n8n

El agente requiere credenciales personalizadas para conectarse a servicios externos y ejecutar tareas automatizadas. Sigue estos pasos:

1. Inicia sesión en tu instancia de **n8n**.
2. Sube el archivo correspondiente de flujo desde el repositorio a **n8n**:
   - Usa la opción de **Importar flujo** dentro de n8n y selecciona el archivo `.json` adecuado.
3. Configura las credenciales necesarias para los servicios utilizados en el flujo:
   - Navega a la sección de **Credenciales** en n8n.
   - Agrega tus credenciales personalizadas según los servicios mencionados en el flujo.

### Paso 3: Ejecutar el Agente

Con las credenciales configuradas, inicia el agente ejecutando el flujo dentro de n8n. También puedes personalizar los flujos según tus necesidades.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un **issue** o envía un **pull request** para sugerir cambios o reportar problemas.

## Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE).

