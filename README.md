# 📚 Gestión de Libros Web

## ✨ Descripción
**Gestión de Libros Web** es una aplicación web simple para gestionar libros, permitir agregar nuevos registros y visualizar los libros existentes mediante una conexión a un servidor local. El proyecto utiliza tecnologías como **HTML, CSS, JavaScript** y **APIs REST** para la gestión de datos.

## 🛠 Tecnologías Utilizadas
- 🌐 **HTML5** y **CSS3** para la estructura y el diseño de la interfaz.
- 💻 **JavaScript** para la funcionalidad del lado del cliente.
- 🔗 **API REST** para la interacción con el servidor local y la base de datos.

## 📥 Instalación y Configuración

### 1️⃣ Requisitos previos
- Tener instalado un servidor local que gestione las rutas `POST` y `GET` para agregar y consultar libros (por ejemplo, Node.js o cualquier servidor de tu elección).
- Asegúrate de que el servidor esté corriendo en **`http://localhost:3000`** o modifica la URL en el código si es necesario.

### 2️⃣ Instalación del Proyecto
1. Clona el repositorio:
    ```bash
    git clone https://github.com/usuario/gestion-libros-web.git
    ```

2. Accede al directorio del proyecto:
    ```bash
    cd gestion-libros-web
    ```

3. Abre el archivo `index.html` en tu navegador para visualizar la aplicación.

### 3️⃣ Configuración del Servidor
Para que la aplicación funcione correctamente, debes configurar el servidor para manejar las siguientes rutas:

- **POST `/add-book`**: Para agregar un nuevo libro.
- **GET `/get-data`**: Para obtener todos los libros y mostrarlos en la tabla.

Asegúrate de que el servidor esté preparado para recibir solicitudes JSON.

## 🚀 Uso

1. **Agregar un nuevo libro**:
   - Completa el formulario con el título, autor, fecha y ISBN del libro.
   - Haz clic en **"Agregar Libro"** para enviar los datos al servidor.
   - El servidor recibirá los datos y los almacenará (si está configurado correctamente).

2. **Consultar los libros existentes**:
   - Haz clic en **"Conectar a la Base de Datos"** para obtener todos los libros almacenados en el servidor y mostrarlos en la tabla.

## 👨‍💻 Autor
**ChrisBarone** ✍️

## 📜 Licencia
Este proyecto es de uso personal o académico y no tiene licencia definida.
