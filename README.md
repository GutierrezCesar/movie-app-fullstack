# 🎬 Movie App Fullstack

Aplicación web desarrollada para gestionar un catálogo de películas. Consta de un backend en Java con Spring Boot conectado a una base de datos MySQL y un frontend que permite visualizar, registrar y listar películas.

---

## 🚀 Tecnologías utilizadas

### Backend:
- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL
- Maven

### Frontend:
- HTML5
- CSS3
- JavaScript

---

## 📦 Estructura del proyecto
movie-app-fullstack/
├── Backend/ # Proyecto backend (Spring Boot)
│ └── src/...
├── Frontend/ # Archivos estáticos (HTML, CSS, JS)
│ └── index.html
├── README.md
└── ...

---

## 🛠️ Instalación y ejecución

### 1. Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/movie-app-fullstack.git
cd movie-app-fullstack
```
2. Configurar base de datos MySQL
Crea una base de datos llamada peliculas_db (o el nombre que hayas usado) y configura tu archivo
spring.datasource.url=jdbc:mysql://localhost:3306/peliculas_db
spring.datasource.username=TU_USUARIO
spring.datasource.password=TU_PASSWORD
spring.jpa.hibernate.ddl-auto=update
3. Ejecutar el backend
cd Backend
./mvnw spring-boot:run
4. Abrir el frontend
Abre el archivo index.html dentro de la carpeta Frontend/ con tu navegador.
📸 Capturas
![WhatsApp Image 2025-07-19 at 16 08 05_b4d512aa](https://github.com/user-attachments/assets/f33bce27-4f86-490a-8ea0-2eb1d9759f75)
![WhatsApp Image 2025-07-19 at 16 08 17_23347bf7](https://github.com/user-attachments/assets/4fe1500c-0845-4119-ab03-48c9cf2438c4)

