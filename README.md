Cálculo de Impuestos de un Vehículo

Descripción

El presente proyecto es el resultado de un aplicativo desarrollado en Java bajo el patrón conocido como Modelo – Vista – Controlador (MVC), esto nos permite deducir el valor del impuesto de un auto teniendo en cuenta información como su marca, modelo, año de fabricación, cilindraje, valor de avalúo comercial y el tipo de uso final (particular o público).
•	En este caso implementamos una herramienta de interfaz gráfica denominada (GUI) en Swing utilizando NetBeans para optimizar la experiencia del usuario final.
•	Utilizamos las tarifas oficiales de Colombia teniendo en cuenta fuentes oficiales para el cálculo del valor de los impuestos.

Datos Solicitados para el Cálculo

Con el objetivo de obtener un resultado preciso del impuesto a los autos, el usuario final debe ingresar la siguiente información al formulario:

•	Marca y modelo del vehículo.
•	Año de fabricación.
•	Cilindraje.
•	Avalúo Comercial (Se debe consultar previamente).
•	Tipo de uso (Particular o Público).



Tarifas Aplicadas

El valor del respectivo impuesto se calcula teniendo en cuenta el valor comercial del automóvil:

•	1.5% para autos que tienen un valor comercial hasta $54.057.000 COP.
•	2.5% para autos con un valor comercial entre $54.057.001 y $121.635.000 COP.
•	3.5% para autos con un valor comercial mayor a $121.635.000 COP.
•	Se maneja un descuento del 20% para autos de uso público.

Instalación y Uso

1.	Clonar el repositorio
Si utilizas git, ejecuta el siguiente comando:
git clone https://github.com/tu-usuario/nombre-del-repositorio.git
O descárgalo en formato .zip desde GitHub y extráelo en tu computadora.

2.	Abrir en NetBeans

1.	Abre NetBeans
2.	Ve a Archivo > Abrir Proyecto
3.	Selecciona la carpeta del proyecto y presiona Abrir.

3.	Ejecutar Aplicación
   
Compila el código en NetBeans.


Tecnologías Utilizadas

	Java 8 o superior
	Swing para la GUI
	NeatBeans IDE (opcional, pero recomendado)
	Patrón de diseño MVC

Estructura del Proyecto
El proyecto está diseñado bajo el patrón MVC, con tres paquetes principales:
📦 src/
 ┣ 📂 model/         #Contiene la lógica de cálculo del impuesto.
 ┃ ┣ 📜 Impuesto.java
 ┣ 📂 view/          #Contiene la interfaz gráfica.
 ┃ ┣ 📜 ImpuestosView.java
 ┣ 📂 controller/    #Maneja la comunicación entre la vista y el modelo.
 ┃ ┣ 📜 ImpuestosController.java


Características Clave

	Interfaz gráfica intuitiva: Fácil de manejar y navegación intuitiva
	Cálculo preciso: Sustentado en las tarifas actualizadas de Colombia de fuentes oficiales.
	Validación de datos: Manejo de errores en la entrada de usuario.
	Diseño modular: Utilización del patrón MVC para llevar a cabo el mantenimiento del código.
	Formato del resultado: Evidencia el resultado con dos decimales.

Referencias

•	Ministerio de Transporte de Colombia: www.mintransporte.gov.co

•	Documentación Oficial de Java Swing: docs.oracle.com
