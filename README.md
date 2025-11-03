TiendaPOO — Sistema de Gestión de Compras en Java

(Descripción General)

TiendaPOO es un proyecto académico desarrollado en Java bajo el paradigma de Programación Orientada a Objetos (POO).
El objetivo es modelar una tienda virtual con un ecosistema de clases que representan clientes, productos, categorías, compras y administración del sistema.

Este proyecto forma parte del curso Programación Orientada a Objetos (POO) de la Universidad EIA, y está implementado completamente en Java (IntelliJ IDEA) aplicando conceptos de:

-> Clases y objetos

-> Encapsulamiento

-> Herencia

-> Clases abstractas e interfaces

-> Agregación y composición

-> Uso de colecciones genéricas (ArrayList)

-> Manejo de relaciones entre objetos

(Estructura del Proyecto)

El sistema contiene 17 clases principales, organizadas de acuerdo con su función dentro del modelo:

Tipo	Clases
Usuarios y Roles	Usuario (abstracta), Cliente, AdministradorUsuario, AdministradorContenido, DuenaSakura
Tienda / Compras	Producto, Categoria, Carrito, LineaCarrito, Compra, LineaCompra, MetodoPago
Producción / Fábrica	Fabrica, TrabajadorEsclavizado, RegistroEsclavos, DesarrolladorProducto
Control y jerarquía	ConsejoSombrio

Ejecución del sistema	Main (menú interactivo)

-> Funcionalidades Principales

1. Gestión de clientes: creación, autenticación básica y métodos de pago.

2. Carrito de compras: agregar, listar o eliminar productos antes de confirmar la compra.

3. Simulación de compra: descuento automático de stock y registro en el historial del cliente.

4. Gestión de fábricas y trabajadores: modela relaciones jerárquicas y registros internos.

5.Jerarquía administrativa: permite interacción de roles como administradores y dueña (DuenaSakura).

6.Persistencia en memoria: los datos se mantienen en ejecución usando listas (ArrayList).

(Requisitos del Sistema)

Lenguaje: Java 8 o superior

IDE recomendado: IntelliJ IDEA Community Edition

Dependencias externas: ninguna (usa solo librerías estándar de Java)

(Ejecución del Proyecto)

Clonar el repositorio:

git clone https://github.com/tuusuario/TiendaPOO.git


Abrir el proyecto en IntelliJ IDEA:

Selecciona la carpeta del proyecto.

Asegúrate de que el SDK esté configurado (Java 8+).

Todos los archivos .java deben estar dentro de la carpeta src/.

Ejecutar el sistema:

Abre Main.java

Clic derecho → Run 'Main.main()'

Interacción en consola:

El sistema mostrará un menú con opciones:

1. Ver catálogo de productos
2. Agregar producto al carrito
3. Ver carrito actual
4. Confirmar compra
5. Ver historial de compras
6. Salir

(Conceptos POO Aplicados)
Concepto	Ejemplo en el Proyecto
Encapsulamiento	Atributos privados con getters/setters
Herencia	Cliente, AdministradorUsuario y DuenaSakura heredan de Usuario
Composición	Carrito contiene LineaCarrito, Compra contiene LineaCompra
Agregación	Categoria contiene una lista de Producto
Abstracción	Clase base Usuario como modelo genérico
Polimorfismo	Diferentes roles de usuario ejecutando acciones distintas
Colecciones genéricas	Uso de ArrayList<T> para almacenar entidades dinámicamente Ejemplo de Ejecución

(SISTEMA DE TIENDA - POO EIA)

Ingrese su nombre: Isaac Mejía
Ingrese su email: isaac@eia.edu.co
Ingrese una contraseña: ****
Dirección de envío: Calle 10 #5
Teléfono: 3216549870

 MENÚ PRINCIPAL
1. Ver catálogo de productos
2. Agregar producto al carrito
3. Ver carrito actual
4. Confirmar compra
5. Ver historial de compras
6. Salir

(Autores y Créditos)

Isaac Mejía Estrada – Estudiante de Ingeniería de sitemas
Thomas gonzales - Estudiante Ingenieria de sistemas

Materia: Programación Orientada a Objetos

Universidad EIA – Proyecto académico de segundo semestre
