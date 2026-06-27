Proyecto: Sistema de Control de Restaurante
Estudiante: Dorys Jeaneth Torres Guerrero

Descripción del Sistema
El propósito de este sistema es administrar de manera eficaz las solicitudes en un restaurante, habilitando la entrada de productos, información de clientes y la gestión de ventas, el diseño tiene como objetivo automatizar las funciones básicas de manejo de datos dentro de un entorno modular.

Estructura del Proyecto

Este proyecto se ha estructurado de manera modular para optimizar el mantenimiento y permitir el crecimiento:

modelos: Aquí se encuentran las clases principales (Producto, Cliente) que simbolizan las entidades dentro del sistema.

servicios: Este directorio alberga la lógica empresarial (Restaurante), que se encarga de manejar los objetos y dirigir las operaciones esenciales.

main. py: Este archivo sirve como la puerta de entrada a la aplicación, donde se crean los objetos y se llevan a cabo las pruebas del sistema.

Tipos de Datos Utilizados

Dentro de las clases, se han empleado los siguientes tipos de datos para garantizar que la información se mantenga íntegra:

str (Cadena): Para atributos como nombres, correos electrónicos y códigos de identificación.

int (Entero): Para representar números de cantidad o edad.

float (Flotante): Para expresar precios o valores monetarios.

bool (Booleano): Para indicar estados de validación o disponibilidad (por ejemplo: Verdadero/Falso).

Reflexión: 

La adopción de un enfoque modular en un proyecto, utilizando nombres de identificación claros y estructuras adecuadas de datos, es crucial debido a las siguientes razones:

Nombres descriptivos: Mejoran la claridad del código, un nombre de variable que sea explicativo permite a cualquier otro desarrollador (o a uno mismo en el futuro) entender la función de un dato sin necesidad de consultar documentación adicional.

Tipos de datos apropiados: Ayudan a que Python administre la memoria de manera eficaz y evitan errores de lógica durante operaciones matemáticas o comparaciones.

Uso de listas: Las listas son esenciales en un sistema modular, ya que posibilitan el almacenamiento de grupos de objetos (como productos o clientes) de manera dinámica, facilitando procesos de recorrido, filtrado y enormes cálculos sobre los datos.
