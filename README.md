 SISTEMA DE TORNEO DE FÚTBOL (JAVA)

Proyecto académico desarrollado en Java que modela la gestión integral de un torneo de fútbol, contemplando jugadores, entrenadores, equipos, partidos, estadísticas y generación de reportes, aplicando principios de Programación Orientada a Objetos.

--

 OBJETIVOS DEL PROYECTO

Simular un sistema que permita:
- Administrar torneos de fútbol de distinta duración
- Gestionar equipos, jugadores y entrenadores
- Registrar partidos y estadísticas por jugador
- Aplicar reglas de negocio deportivas
- Generar reportes y tablas estadísticas del torneo

El foco del proyecto está puesto en el modelado del dominio, la implementación de casos de uso reales y la correcta aplicación de conceptos OO.

--

 CONCEPTOS APLICADOS

- Programación Orientada a Objetos (POO)
- Encapsulamiento
- Herencia (Persona)
- Polimorfismo
- Separación de responsabilidades
- Uso de colecciones (ArrayList)
- Clases de dominio y clases de reporte
- Métodos de negocio y validaciones
- Ordenamiento de listas
- Clase de prueba para validación de casos de uso

--

 ESTRUCTURA DEL PROYECTO
src/

-modelo/

  - Persona.java
  - Jugador.java
  - Entrenador.java
  - Equipo.java
  - Torneo.java
  - Partido.java
  - Estadistica.java
  - Sistema.java
  - Goleador.java
  - Asistencia.java
  - Posicion.java
  - Ganador.java

-test/

  - Test.java

 modelo: contiene las entidades del dominio, la lógica del sistema y las clases auxiliares de reporte

 test: contiene la clase de prueba donde se validan los casos de uso solicitados

--

 CASOS DE USO IMPLEMENTADOS

- Alta, baja y búsqueda de jugadores, entrenadores, equipos y torneos
- Asociación de jugadores a equipos
- Asociación de equipos a torneos
- Registro de partidos y estadísticas
- Búsquedas por criterios (fecha, táctica, fundación)
- Cálculo de:
-goles y asistencias por jugador
-altura promedio por equipo
-puntos acumulados
- Generación de:
-tabla de posiciones
-tabla de goleadores
-tabla de asistidores
-listado de ganadores por fecha

--

 EJECUCIÓN

1. Importar el proyecto en un IDE Java (por ejemplo, Eclipse)
2. Ejecutar la clase `Test.java`
3. Observar la salida por consola, donde se validan las distintas operaciones del sistema

--

 NOTAS

- Proyecto realizado en el marco de un laboratorio académico grupal
- No utiliza frameworks externos
- Enfocado en lógica de negocio, diseño del dominio y claridad del código

--

 AUTOR

Leandro Vera