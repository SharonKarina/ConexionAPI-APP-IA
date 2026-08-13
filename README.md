# ConexionAPI-APP-IA

## Paso a paso para la configuración y ejecución del proyecto

### 1. Crear los archivos principales del proyecto

Inicialmente, se crean los archivos Python que contendrán la lógica y los métodos necesarios para realizar las pruebas y ejecutar la conexión con la API:

* `prueba_entorno.py`: archivo destinado a realizar pruebas de configuración y verificar que el entorno de desarrollo funcione correctamente.
* `app_gemini.py`: archivo principal que contiene los métodos necesarios para realizar la conexión y ejecutar las funcionalidades asociadas a la API de Gemini.

### 2. Crear el archivo `requirements.txt`

Se crea el archivo `requirements.txt`, en el cual se registran las librerías y dependencias necesarias para el funcionamiento del proyecto.

Este archivo permite instalar posteriormente todas las dependencias requeridas de manera sencilla y organizada.

### 3. Crear el entorno virtual

Desde la terminal de Visual Studio Code, ubicándose en la carpeta raíz del proyecto, se ejecuta el siguiente comando:

```bash
python -m venv venv
```

Este comando crea un entorno virtual denominado `venv`, con el objetivo de mantener aisladas las dependencias del proyecto de las demás instalaciones de Python presentes en el equipo.

### 4. Activar el entorno virtual

Una vez creado el entorno virtual, se procede a activarlo.

**En Windows:**

```bash
venv\Scripts\activate
```

Al activarlo correctamente, la terminal mostrará normalmente el nombre del entorno virtual al inicio de la línea de comandos:

```text
(venv)
```

### 5. Instalar las librerías necesarias

Con el entorno virtual activado, se instalan las dependencias definidas en el archivo `requirements.txt` mediante el siguiente comando:

```bash
pip install -r requirements.txt
```

De esta manera, se instalan todas las librerías necesarias para ejecutar el proyecto dentro del entorno virtual.

### 6. Ejecutar los archivos Python

Finalmente, se ejecutan los archivos creados para verificar el funcionamiento del entorno y de la conexión con la API.

Para ejecutar la prueba del entorno:

```bash
python prueba_entorno.py
```

Posteriormente, para ejecutar la aplicación:

```bash
python app_gemini.py
```

Con estos pasos se completa la configuración del entorno de desarrollo, la instalación de las dependencias y la ejecución del proyecto de conexión con la API.
