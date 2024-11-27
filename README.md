<h1>Identificador de Provincia por Celular</h1>
Este repositorio contiene un proyecto web simple que permite identificar la provincia asociada a un número de celular argentino. Utiliza HTML, CSS y JavaScript para crear una interfaz interactiva y amigable.

<h4>Características:</h4>
Identificación de provincia: Basado en el código de área del número telefónico ingresado, el sistema determina la provincia correspondiente.
Interfaz moderna: Utiliza estilos CSS con gradientes y animaciones para una experiencia visual agradable.
Fácil de usar: La entrada del usuario se procesa automáticamente para identificar el código de área.
Vista Previa
El sitio incluye un campo de entrada para el número de teléfono y un botón para realizar la identificación. Una vez ingresado el número, se muestra la provincia correspondiente.

<h4>Requisitos:</h4>
Un navegador web moderno para ejecutar el código.
Archivo index.html disponible en el repositorio.

<h4>Cómo usar:</h4>
Clona el repositorio:

bash
Copiar código
git clone https://github.com/tuusuario/identificador-provincia-celular.git
Abre el archivo index.html: Usa cualquier navegador web para abrir el archivo.

Ingresa un número de celular: Introduce un número con formato internacional (ejemplo: +54 (11) 67482209) o local.

Haz clic en "Identificar": El sistema analizará el código de área y mostrará la provincia correspondiente.

<h4>Funcionalidades técnicas:</h4>

JavaScript:
Normalización del número: Elimina caracteres especiales como paréntesis, guiones y espacios. Además, gestiona formatos con +54, 54, o números con prefijo 9.

Búsqueda del código de área: Determina el código de área más largo posible, comenzando por una longitud de 4 y reduciendo hasta 2 dígitos.

Diccionario de códigos de área: Contiene asociaciones clave-valor entre códigos y provincias argentinas.

CSS:
Diseño adaptable: La página está centrada y utiliza gradientes para un fondo moderno y atractivo.

Estilo interactivo: Los botones tienen efectos de hover que mejoran la experiencia de usuario.

HTML:
Estructura simple: Contiene una etiqueta de entrada, un botón y una sección de resultados.

Personalización:
Puedes actualizar el archivo index.html para añadir más códigos al diccionario o cambiar el estilo visual en la sección <style>.

<h4>Autor:</h4>
Desarrollado por Jorge Marquez.
