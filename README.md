# Rutea - Colección de Pruebas de API (Bruno)

Este repositorio contiene la colección oficial de **Bruno** para la interacción y prueba de los servicios de **Rutea**. Rutea es una plataforma avanzada para la gestión y optimización de rutas geográficas, proporcionando herramientas para el cálculo de trayectorias óptimas y alternativas basadas en algoritmos de grafos.

## 🚀 Descripción del Proyecto

La colección está organizada de manera modular para facilitar la prueba de los diferentes servicios del ecosistema Rutea:

- **🔐 Autenticación (`auth/`)**:
  - `login`: Gestión de acceso mediante credenciales.
  - `refresh`: Renovación de tokens de acceso (JWT).

- **🛣️ Gestión de Rutas (`rutas/`)**:
  - `Ruta optima`: Cálculo de la mejor ruta entre dos puntos geográficos.
  - `Ruta alternativa`: Propuesta de trayectos secundarios.
  - `crear/edit rutas`: CRUD para la administración de rutas en el sistema.
  - `grafo`: Representación interna de la red de nodos y aristas.
  - `nodo cercano`: Búsqueda de puntos de interés o nodos viales próximos a una coordenada.

- **👥 Usuarios y Personal (`user/`, `persona/`)**:
  - Gestión de perfiles de usuario y datos personales asociados.

- **📧 Notificaciones (`mail/`)**:
  - Pruebas para los servicios de mensajería y notificaciones del sistema.

## 🛠️ Cómo empezar

1. **Instalar Bruno**: Descarga e instala [usebruno.com](https://www.usebruno.com/).
2. **Importar Colección**:
   - Abre Bruno.
   - Haz clic en `Open Collection`.
   - Selecciona la carpeta raíz de este repositorio.
3. **Configuración de Entorno**:
   - Selecciona el entorno deseado (`Local`, `Dev`, `Prod`) en la esquina superior derecha.
   - La variable `{{api}}` se ajustará automáticamente según el entorno seleccionado.

## ⚙️ Tecnologías Utilizadas
- **Bruno**: Cliente HTTP open-source basado en archivos locales (Git friendly).
- **JSON**: Formato de intercambio de datos para los cuerpos de las peticiones.
- **Bearer Token**: Esquema de autenticación para rutas protegidas.

---
*Desarrollado para el proyecto Rutea - Gestión Inteligente de Rutas.*
