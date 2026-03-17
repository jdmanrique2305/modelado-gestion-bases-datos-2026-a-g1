# Reflexión: PostgreSQL vs MySQL con Docker

**Asignatura:** Modelado y Gestión de Bases de Datos  

En este laboratorio aprendí a levantar dos bases de datos, PostgreSQL y MySQL, usando contenedores Docker. Fue interesante ver cómo con pocos archivos de configuración se puede tener un entorno de base de datos funcionando sin necesidad de instalaciones complejas.

Algo que noté es que ambos motores manejan SQL de forma muy similar. Los comandos para crear tablas, insertar y consultar datos son prácticamente iguales. La diferencia más notable está en detalles pequeños, como que PostgreSQL usa `SERIAL` para el autoincremento mientras que MySQL usa `AUTO_INCREMENT`, o que para cambiar de base de datos PostgreSQL usa `\c` y MySQL usa `USE`.

En cuanto a Docker, lo más valioso fue entender que puedo tener ambos motores corriendo al mismo tiempo en el mismo equipo sin que interfieran entre sí, algo que con una instalación tradicional sería mucho más difícil de lograr.

En general, considero que PostgreSQL tiene una sintaxis más cercana al estándar SQL, mientras que MySQL resulta un poco más sencillo de configurar al inicio. Ambos son herramientas útiles y la elección entre uno u otro depende del proyecto.


