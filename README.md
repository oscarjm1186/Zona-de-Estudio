# 🚀 Space Lab Academy

Esto es una mini plataforma educativa estática, ágil y de código abierto, diseñada originalmente como una herramienta de apoyo académico integral para mi hija y enfocada en el nivel de estudios que va cursando en CECyT 11. 

Es una interfaz simple donde utilizo una estética *Glassmorphism* con Dark Mode nativo para reducir la fatiga visual durante el estudio.

## ✨ Características Principales

* **🔒 Zona Privada (Client-Side Auth):** Pantalla de bloqueo integrada con memoria de sesión mediante `sessionStorage`. El usuario ingresa la clave una vez y puede navegar fluidamente sin interrupciones hasta que cierra el navegador.
* **📚 Hub de Estudio Centralizado:** Un panel de control (Dashboard) que conecta 9 materias fundamentales.
* **⚡ Simuladores de Exámenes:** Entornos de prueba en formato HTML aislados para practicar sin distracciones. *(Soporte para MathJax en fórmulas de física y matemáticas).*
* **🗂️ Fichas Didácticas (Flashcards 3D):** Módulo de repaso rápido con animaciones CSS (Flip card) para memorizar conceptos clave.
* **📖 Temarios Integrados:** Ventanas modales (Pop-ups) con los planes de estudio simplificados accesibles a un clic.
* **☁️ Conexión a la Nube:** Botones integrados para redirigir a repositorios de Google Drive (Libros) y listas de reproducción (Media/Podcasts).

## 🛠️ Tecnologías Utilizadas

Este proyecto es deliberadamente ligero y no requiere servidores (Serverless) ni bases de datos complejas.
* **HTML5 Semántico**
* **CSS3 Nativo** (Flexbox, Grid, Animaciones 3D)
* **JavaScript (Vanilla JS)** para la lógica de modales, autenticación básica y flashcards.
* **FontAwesome** para la iconografía vectorial.

## 🚀 Cómo usar este proyecto (Para otros desarrolladores o educadores)

Si deseas clonar este proyecto para mejorarlo, adelante:

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/TU_USUARIO/space-lab-academy.git](https://github.com/TU_USUARIO/space-lab-academy.git)
    ```
2.  **Configura la contraseña:** Abre el archivo `index.html` y modifica la constante `correctPass` en la sección del script con la clave que desees.
3.  **Vincula tus recursos:** En el mismo `index.html`, busca las etiquetas `LINK_DRIVE` y `LINK_MEDIA` y reemplázalas con tus propios enlaces.
4.  **Alimenta las Flashcards:**
    Agrega tus propias preguntas en la constante `flashcardsDB` dentro del JavaScript del `index.html`.
5.  **Despliegue:**
    Sube la carpeta a cualquier servicio de hosting estático como Netlify, Vercel o GitHub Pages.

---
*Desarrollado por Space Lab Arquitectura. Creando espacios (físicos y digitales) fuera de este mundo.*