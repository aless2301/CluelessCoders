# CluelessCoders
Proyecto para HackPue.
# Future STEM Lab

¡Bienvenidos a **Future STEM Lab**! 👋

Esta es una plataforma educativa diseñada para **inspirar a estudiantes de bachillerato en el mundo de las carreras STEM** (Ciencia, Tecnología, Ingeniería y Matemáticas). Nuestro objetivo es mostrar cómo se aplican estas áreas de forma práctica y divertida, ayudando a los jóvenes a tomar decisiones informadas sobre su futuro profesional.

## 🚀 Sobre el Proyecto

El sitio web de Future STEM Lab ofrece:

* **Cursos en línea:** Contenido educativo sobre temas como electrónica con **Tinkercad**, programación con **Micro:bit** y biotecnología con **kits de ADN**.
* **Experiencia interactiva:** Una sección de **"Revisor de Circuitos IA"** que permite a los estudiantes subir una foto de su circuito para recibir retroalimentación automática y, si es aprobado, generar un diploma digital.
* **Contenido claro y accesible:** La interfaz es simple y amigable, con un diseño que facilita la navegación entre las secciones.
## 💡 Características Clave

* **Diseño Responsivo:** El sitio está optimizado para su visualización en diferentes dispositivos.
* **Integración de IA (simulada):** La página `ia.html` demuestra el concepto de una herramienta de revisión automatizada de proyectos.
* **Generación de Diplomas:** Los estudiantes pueden obtener un diploma personalizado en formato PNG al aprobar sus proyectos.

* ## 🚀 Puesta en Marcha

Para ejecutar este proyecto en tu propia máquina, sigue estos pasos:

1.  *Clonar el repositorio:*
    bash
    git clone https://github.com/tu-usuario/tu-repositorio.git
    cd tu-repositorio
    

2.  *Instalar las dependencias del servidor:*
    (Asegúrate de tener Node.js instalado)
    bash
    npm install
    

3.  *Configurar las variables de entorno:*
    *   Crea un archivo llamado .env en la raíz del proyecto.
    *   Añade tu clave de API de Google AI Studio:
        
        API_KEY=TU_API_KEY_DE_GOOGLE_AI_AQUI
        
    *   *¡Importante!* Asegúrate de que el archivo .env esté incluido en tu .gitignore para no subir tu clave secreta a GitHub.

4.  *Iniciar el servidor:*
    bash
    node server.js
    

5.  *¡Abrir la aplicación!*
    Abre tu navegador y ve a http://localhost:3000/index.html (o la página que tenga el botón para ir al revisor).

