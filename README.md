# Gestion-Libros-Electronicos
Proyecto de la materia PROGRAMACION ORIENTADA A OBJETOS 1-SIN-3A, de la carrera de Ingeniería en Software
Descripción del proyecto

El Sistema de Gestión de Libros Electrónicos es un proyecto desarrollado como parte de la carrera de Ingeniería en Software. Su propósito es facilitar la administración de una biblioteca digital mediante herramientas que permitan gestionar libros, usuarios, préstamos y devoluciones.

El sistema será desarrollado utilizando Go (Golang) y contará con servicios web REST para permitir la comunicación e intercambio de información con aplicaciones externas mediante solicitudes HTTP y respuestas en formato JSON.

# Objetivo general

Desarrollar un sistema de gestión de libros electrónicos que permita administrar de manera organizada la información de libros y usuarios, controlar los préstamos y devoluciones, realizar búsquedas y generar reportes, incorporando servicios web REST para facilitar la integración con otras aplicaciones.

# Funcionalidades principales

El sistema contempla los siguientes módulos:

-Gestión de libros: registrar, consultar, actualizar y eliminar libros electrónicos.

-Gestión de usuarios: registrar, consultar, modificar y desactivar usuarios.

-Préstamos y devoluciones: controlar la disponibilidad de libros y administrar los préstamos y devoluciones.

-Búsqueda y consulta: localizar libros por título, autor o categoría.

-Reportes y estadísticas: consultar información sobre libros registrados, usuarios y préstamos.

-Servicios web REST: permitir la comunicación con aplicaciones externas mediante endpoints HTTP e intercambio de datos JSON.

# Tecnologías y herramientas

-Lenguaje de programación: Go (Golang).

-Servicios web: arquitectura REST.

-Protocolo de comunicación: HTTP.

-Formato de intercambio de datos: JSON.

# Paquetes estándar de Go:

-fmt: presentación de mensajes y resultados.

-strings: procesamiento de texto.

-time: gestión de fechas.

-encoding/json: codificación y decodificación JSON.

-os: gestión de archivos.

-errors: manejo de errores.

-slices: manipulación de colecciones.

-net/http: implementación del servidor y servicios web.

# Aplicación de la programación funcional

Se incorporarán principios de programación funcional mediante:

-Uso de funciones independientes y reutilizables.

-Implementación de funciones puras cuando sea posible.

-Reducción de modificaciones innecesarias de datos.

-Separación de la lógica de negocio de las operaciones externas.

-Organización modular del código.

# Estructura general del sistema

El proyecto se organizará en módulos para facilitar su desarrollo y mantenimiento:

<img width="617" height="476" alt="image" src="https://github.com/user-attachments/assets/6dc3edad-f1a5-4788-a7d8-5bb543bd93bb" />



Nota: Esta estructura es una propuesta inicial y podrá modificarse durante el desarrollo.

# Funcionamiento general del sistema
El sistema iniciará desde main.go, conectando los diferentes módulos para administrar libros, usuarios, préstamos y devoluciones. Cuando un usuario solicite un préstamo, se verificará que esté registrado y activo, y que el libro se encuentre disponible. Si las condiciones se cumplen, se registrará el préstamo y se actualizará la información en los archivos JSON de la carpeta datos/.

Además, el sistema permitirá buscar libros, gestionar usuarios, registrar devoluciones y generar reportes estadísticos. Mediante la carpeta api/, se implementarán servicios web REST para permitir la comunicación con aplicaciones externas utilizando solicitudes HTTP e intercambio de información en formato JSON.

# Alcance del proyecto

El proyecto contempla el desarrollo de las funcionalidades principales para administrar una biblioteca digital, incluyendo la gestión de libros, usuarios, préstamos, devoluciones, búsquedas, reportes y servicios web REST.

El almacenamiento de información y la organización definitiva de los componentes se establecerán durante la implementación.

No se contempla inicialmente el desarrollo de una aplicación móvil independiente ni una plataforma comercial de venta de libros.

# Estado del proyecto

En fase de planificación y diseño.

Las funcionalidades descritas representan los objetivos previstos para el desarrollo del sistema y se implementarán progresivamente.

# Autor

Moises Sandoval - Estudiante Ingenieria en Software 
