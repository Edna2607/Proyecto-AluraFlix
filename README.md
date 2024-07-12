# AluraFlix Challenge - Oracle One Education & Alura Latam

AluraFlix es una plataforma diseñada para gestionar vídeos, con funcionalidades como listar, registrar, actualizar y eliminar videos, implementando React con JavaScript. Este proyecto permite aplicar y mejorar habilidades en React, incluyendo componentización, uso de hooks, consumo de API, rutas, entre otros conceptos avanzados.

En esta aplicación, los usuarios pueden:
- Listar videos.
- Registrar nuevos videos con título, descripción, URL de la imagen y URL del video.
- Actualizar la información de los videos.
- Eliminar videos de la lista.


## Mi proceso

### Desarrollo continuo

En el futuro, me gustaría:
- Integrar una base de datos real para almacenar los videos.
- Implementar autenticación de usuarios.
- Añadir más funcionalidades, como la búsqueda y filtrado de videos.
- Guardar la informacion en una base de Datos

## Agradecimientos

Gracias a Alura Latam y Oracle Next Education por la oportunidad de participar en esta Especializacion Front End. Agradezco también a todos los profes por compartir su conocimiento. 

## Instrucciones de instalación

Para ejecutar este proyecto localmente, sigue estos pasos:

1. **Clona el repositorio**:

    ```bash
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    ```

2. **Instala las dependencias**:
    Asegúrate de tener Node.js instalado en tu máquina. Luego, instala las dependencias del proyecto:

    ```bash
    npm install
    ```

3. **Inicia el servidor JSON**:
   JSON-Server se utilizará para simular una API. Ejecuta el siguiente comando para iniciar el servidor:

    ```bash
    npx json-server --watch ./src/data/db.json
    ```

    El servidor se ejecutará en `http://localhost:3000`.

4. **Inicia la aplicación**:
    Ejecuta el siguiente comando para iniciar la aplicación:

    ```bash
    npm run dev
    ```
    La aplicación se ejecutará en `http://localhost:5173`.

    ¡Listo! Ahora puedes interactuar con la plataforma AluraFlix y gestionar tus videos. 🚀