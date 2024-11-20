PASOS A SEGUIR PARA EL CORRECTO FUNCIONAMIENTO DEL PROYECTO

1. Instalación de Python

Descargar e instalar Python (se ha utilizado la versión 3.11) desde: https://www.python.org/downloads/.

2. Instalar Tkinter
Tkinter viene preinstalado con Python. Para verificar, ejecuta:

bash
python -m tkinter

3. Instalar MySQL
Descargar e instalar MySQL Server desde: https://dev.mysql.com/downloads/mysql/.
Configurar MySQL con un usuario (root) y contraseña (curso).

4. Bibliotecas de Python
Instalar las bibliotecas necesarias ejecutando:


bash
pip install mysql-connector-python matplotlib pandas ttkbootstrap

5. Configuración de la Base de Datos
Abre MySQL Workbench.
Crea la base de datos y tabla ejecutando el script SQL incluido en el proyecto. La base de datos ha sido ligeremante modificada incluyendo un autoincrement a la primary key para facilitar el manejo de IDs

6. Ejecución del Programa
   
6.1 Descarga del Proyecto

Clona este repositorio o descarga el archivo ZIP y descomprímelo en tu IDE.

6.2 Ejecutar el Código
Abre el proyecto (previamente descargado) en el IDE y ejecuta el archivo main.py

6.3 Interfaz de Usuario
Al iniciar, encontrarás dos pestañas:
Encuestas: Permite realizar las operaciones CRUD y ordenar los datos.
Gráficos: Genera gráficos de barras o líneas basados en los datos.

7. Uso de la Aplicación
   
7.1 Operaciones CRUD
Agregar Datos: Completa todos los campos y haz clic en el botón "Agregar".
Visualizar Datos: Haz clic en el botón "Mostrar" para cargar todos los registros en la tabla.
Actualizar Datos: Selecciona un registro en la tabla, edita los campos, selecciona el ID que quieres actualizar y haz clic en el botón "Actualizar".
Eliminar Datos: Haz clic en el botón "Eliminar" y selecciona el ID que desees eliminar.

7.2 Ordenar Datos
Selecciona un campo en el menú desplegable "Ordenar por" y haz clic en el botón "Ordenar".

7.3 Exportar a Excel
Haz clic en "Exportar a Excel" para guardar los datos en un archivo .xlsx. Se te pedirá un nombre de archivo.

7.4 Visualización de Gráficos
Selecciona un campo en el menú desplegable "Seleccione campo para graficar".
Escoge el tipo de gráfico (Barras o Líneas) y haz clic en "Graficar".
Los gráficos se generan en la pestaña "Gráficos".
