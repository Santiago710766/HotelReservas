Sistema de Gestión de Reservas de Hotel 
Este es un sistema completo para la gestión de reservas de un hotel, desarrollado en Java utilizando Swing para la interfaz gráfica y aplicando principios de POO avanzada.

Funcionalidades Principales
•	Login con roles: Admin y Recepcionista
•	Gestión de clientes: Registro con validación de cédula única
•	Gestión de habitaciones: Crear, listar y consultar disponibilidad
•	Reservas: Crear reservas, elegir habitaciones disponibles, ver comprobante
•	Estadísticas: Ver totales de clientes, habitaciones disponibles/ocupadas y reservas activas
•	Persistencia: Toda la información se guarda en archivos .txt

Roles y accesos
Login
Al iniciar el programa, se debe iniciar sesión con un usuario y contraseña:
Usuario	Contraseña	Rol
admin	   123	 Administrador
recep	   123 	Recepcionista
Administrador:
•	Puede acceder a todo el sistema: Clientes, Habitaciones, Reservas, Estadísticas
Recepcionista:
•	Solo puede acceder a Clientes y Reservas

¿Cómo compilar y ejecutar?
1. Extrae el archivo .zip en tu computadora
2. Abre la carpeta en Visual Studio Code o cualquier IDE Java (como NetBeans o IntelliJ)
3. Asegúrate de tener JDK 17 o superior instalado
4. Compila y ejecuta el archivo Main.java
javac Main.java
java Main

Estructura del Proyecto
HotelReservas/
│
├── modelo/             # Clases principales: Cliente, Habitacion, Reserva, DAO, Empresa
├── vista/              # Interfaces gráficas (Swing): Paneles, ventanas, login
├── archivos .txt       # Persistencia de datos: clientes.txt, habitaciones.txt, reservas.txt
├── Main.java           # Punto de entrada del programa

Ejemplo de uso
1.	Login como admin o recepcionista
2.	Registra un cliente en la pestaña Clientes
3.	Registra habitaciones (como suite, doble, individual)
4.	Crea una reserva seleccionando un cliente y una habitación disponible
5.	Visualiza estadísticas actualizadas con botón 🔄

Requisitos
•	Java JDK 17 o superior
•	IDE Java (Visual Studio Code, IntelliJ o NetBeans)

Autor
Desarrollado por: Omar Santiago Cornejo Cornejo
