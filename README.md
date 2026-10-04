# API RESTful - Gestión de Clínica Veterinaria 🐾

Este proyecto es una API RESTful diseñada para centralizar y optimizar las operaciones de una clínica veterinaria. Proporciona una arquitectura robusta para gestionar la información de pacientes, registros médicos y operaciones diarias del negocio.

## 🚀 Tecnologías Utilizadas

El proyecto fue desarrollado utilizando el ecosistema Java enfocado en buenas prácticas, escalabilidad y despliegue ágil:

*   **Lenguaje:** Java 17
*   **Framework Principal:** Spring Boot
*   **Persistencia de Datos:** Spring Data JPA e Hibernate
*   **Base de Datos:** MySQL
*   **Herramientas de Desarrollo:** Lombok (para optimización de código base)
*   **Gestión de Dependencias:** Maven
*   **Contenerización:** Docker & Docker Compose (para el entorno de la base de datos)

## ⚙️ Características Principales
*   **Arquitectura RESTful:** Endpoints estructurados lógicamente para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar).
*   **Mapeo Objeto-Relacional (ORM):** Uso de Hibernate y JPA para interactuar de forma segura y eficiente con la base de datos MySQL, manejando las relaciones entre entidades.
*   **Código Limpio:** Reducción de código repetitivo (getters, setters, constructores) mediante la implementación de anotaciones de Lombok.
*   **Despliegue Estandarizado:** Configuración de `docker-compose.yml` para levantar la base de datos MySQL localmente sin necesidad de instalaciones complejas.

## 🛠️ Instalación y Ejecución Local

Si deseas correr este proyecto de manera local, sigue estos pasos:

1.  **Clonar el repositorio:**
    ```bash
    git clone https://github.com/CarlosLlanes-dev/clin_vet.git
    ```
2.  **Levantar la base de datos con Docker:** Asegúrate de tener Docker instalado y ejecutándose. Navega a la raíz del proyecto y ejecuta:
    ```bash
    docker-compose up -d
    ```
3.  **Ejecutar la aplicación Spring Boot:** Puedes abrir el proyecto en IntelliJ IDEA y ejecutar la clase principal, o utilizar Maven desde la terminal:
    ```bash
    mvn spring-boot:run
    ```

La API estará disponible por defecto en el puerto `8080` (ej. `http://localhost:8080`).

## 👨‍💻 Autor

**Carlos Llanes**
Estudiante de Ingeniería en Desarrollo de Software con background analítico en mecatrónica.

*   [Perfil de LinkedIn](https://www.linkedin.com/in/carlosllanes-dev/)
