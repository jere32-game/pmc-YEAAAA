# 🐧 PenguinMod Comments Extension

Una extensión de Google Chrome diseñada para habilitar y gestionar una sección de comentarios integrada directamente en los proyectos de **PenguinMod**. Permite a los usuarios interactuar, dejar opiniones y responder de forma dinámica.

Agradecimientos especiales a **jere32game** por la idea inicial, el desarrollo clave y la moderación del sistema de comentarios.

---

## 📸 Captura de Pantalla

Así es como se ve la sección de comentarios integrada en la plataforma:

![Sección de Comentarios en PenguinMod](https://yyf.mubilop.com/file/573f9fb3/Screenshot_1.png)

---

## ✨ Características principales

- **Comentarios en Tiempo Real:** Escribe y publica opiniones instantáneamente con un límite de hasta 500 caracteres.
- **Respuestas e Hilos:** Responde directamente a otros usuarios para mantener conversaciones organizadas.
- **Sistema de Moderación:** Soporte para comentarios fijados (`Pinned`), verificación de cuentas (`Verified`) y etiquetas de creador (`Creator`).
- **Control de Gestión:** Opciones para eliminar (`Delete`) o desfijar (`Unpin`) comentarios si eres el dueño del proyecto.
- **Contadores de Interacción:** Visualización de reacciones (corazones, aprobaciones y vistas del proyecto).

---

## 🚀 Instalación (Modo Desarrollador)

Como esta extensión se encuentra en desarrollo y se instala de forma local, sigue estos pasos para añadirla a tu navegador Chrome:

1. **Clona o descarga este repositorio:**
   ```bash
   git clone https://github.com
   ```
   *(O simplemente descarga el archivo ZIP desde [el release](https://github.com/jere32-game/pmc-YEAAAA/releases/tag/pmc)).*

2. **Abre la gestión de extensiones en Chrome:**
   - Escribe `chrome://extensions/` en tu barra de direcciones y presiona Enter.

3. **Activa el Modo de Desarrollador:**
   - Activa el interruptor que se encuentra en la esquina superior derecha de la pantalla.

4. **Carga la extensión:**
   - Haz clic en el botón **"Cargar descomprimida"** (Load unpacked) en la esquina superior izquierda.
   - Selecciona la carpeta que contiene los archivos de la extensión (donde se encuentran el `manifest.json` y los scripts).

¡Listo! La extensión ya estará activa y funcionando al navegar en PenguinMod.

---

## 🛠️ Tecnologías utilizadas

- **JavaScript (ES6+)** - Lógica interna de la extensión e inyección de scripts en el DOM.
- **HTML5 & CSS3** - Estructura y estilos de la interfaz de la caja de comentarios (modo oscuro).
- **Chrome Extensions API v3** - Arquitectura base para la compatibilidad moderna con Google Chrome.

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras algún error o tienes ideas para mejorar las funciones de comentario:
1. Haz un **Fork** del proyecto.
2. Crea una rama con tu nueva función (`git checkout -b feature/NuevaMejora`).
3. Haz un **Commit** con tus cambios (`git commit -m 'Añadir nueva mejora'`).
4. Sube la rama (`git push origin feature/NuevaMejora`).
5. Abre un **Pull Request**.
