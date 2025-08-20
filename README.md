# Challenge-literalura-Alura

📚 literAlura: Tu Biblioteca Virtual al Estilo Geek

¿Alguna vez soñaste con tener una biblioteca infinita sin ocupar espacio en tu habitación? ✨ Pues literAlura llega para cumplir ese sueño.
Aquí podrás buscar, registrar y explorar libros y autores, además de descubrir quiénes seguían vivos en un año específico (👀 como si fueras un detective literario).

🎬 Cómo Funciona la Magia

📡 Conexión con Gutendex: Tomamos prestados los libros de la API GutenDex
.

🔄 Conversión Inteligente: Los datos crudos se transforman en objetos Java listos para usarse.

🧹 Limpieza de Datos: Nos aseguramos de no duplicar libros ni autores en la base de datos.

💾 Guardado Seguro: Todo queda almacenado en una base de datos SQL (elige tu favorita: PostgreSQL, MySQL, MariaDB, SQL Server o H2).

🌟 Superpoderes de literAlura

🔍 Buscar libro por título: ¿Tienes un nombre en mente? Encuéntralo al instante.

📖 Listar libros registrados: Tu biblioteca digital organizada y sin polvo.

✍️ Listar autores registrados: Descubre a las mentes detrás de cada obra.

🕵️ Listar autores vivos en un año específico: Ideal para sentirte en un viaje en el tiempo.

🌎 Listar libros por idioma: Porque la literatura no tiene fronteras.

🛠️ Tecnologías que dan vida a este proyecto

☕ Java 11+ – El motor detrás de todo.

🚀 Spring Boot 2.6.4 – Para crear APIs como un rayo.

📦 Spring Data JPA – Manejo elegante de bases de datos.

🗄️ SQL Databases – (PostgreSQL, MySQL, MariaDB, SQL Server, H2).

📚 Jackson – El mago que convierte JSON en objetos Java.

🔧 Maven – Tu aliado para dependencias y builds.

🚀 Cómo ponerlo en marcha
🔑 Prerrequisitos

Java 11 o superior

Maven 3.6+

Una base de datos SQL (a tu elección)


⚙️ Configuración rápida

En application.properties, ajusta tu base de datos:

spring.datasource.url=jdbc:postgresql://localhost:5432/nombre_de_tu_base
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
spring.jpa.hibernate.ddl-auto=update

▶️ Ejecutar

Corre LiteraturaApplication desde tu IDE favorito o desde consola:

mvn spring-boot:run

🖥️ Menú Interactivo

Al ejecutar el programa verás algo como esto:

✨ Bienvenid@ a literAlura ✨
Elige una opción:
1 - Buscar libro por título
2 - Listar libros registrados
3 - Listar autores registrados
4 - Listar autores vivos en un determinado año
5 - Listar libros por idioma
0 - Salir
