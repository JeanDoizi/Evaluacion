Descripción del Proyecto:
Sistema básico de gestión de biblioteca en Java que permite agregar libros, realizar reservas y cancelar reservas. Maneja excepciones personalizadas para situaciones como agregar un libro duplicado, reservar un libro inexistente o cancelar la reserva de un libro no reservado.

Dependencias:

Java: JDK 8 o superior
Maven: Para gestión de dependencias y compilación
Instrucciones para Ejecutar:

Clona o descarga el repositorio.
Abre el proyecto en NetBeans o cualquier IDE compatible con Maven.
Compila y ejecuta la clase Main en el paquete com.mycompany.bibliotecahoy.
Estructura del Proyecto:

Paquete principal: com.mycompany.bibliotecahoy
Biblioteca.java: Gestiona las operaciones de la biblioteca.
Libro.java: Representa un libro.
LibroDuplicadoException.java: Excepción para libros duplicados.
LibroNoDisponibleException.java: Excepción para libros no disponibles.
Main.java: Ejecuta el programa de prueba.
Funcionalidad Adicional:

Sistema de reservas de libros: Permite reservar libros por ISBN, con excepciones para libros no disponibles o inexistentes.
Excepciones y Jerarquía:

LibroDuplicadoException: Excepción para libros duplicados.
LibroNoDisponibleException: Excepción para libros no disponibles.
Ambas extienden la clase Exception, siendo excepciones verificadas.
