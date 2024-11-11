Versión: 1.0
Fecha de lanzamiento: Octubre 2024
Licencia: MIT License

Descripción
Mate-Exploradores es un juego educativo diseñado para estudiantes de primaria, enfocado en fortalecer habilidades en matemáticas a través de preguntas interactivas sobre sumas, restas, multiplicaciones y divisiones. El juego utiliza SQLite para almacenar el progreso de los jugadores de forma local, permitiendo continuar el aprendizaje sin conexión a internet.

Tecnologías utilizadas
Lenguaje de programación: Python 3.8+
Base de datos: SQLite
Interfaz gráfica de usuario (GUI): Tkinter
Dependencias adicionales: sqlite3, tkinter, winsound, PIL (opcional para imágenes)
Requerimientos del sistema
Hardware:

Procesador: Intel Core i3 o superior
Memoria RAM: 4GB o superior
Espacio en disco: Al menos 200 MB disponibles
Software:

Sistema operativo: Windows 7 o superior
Python 3.8 o superior instalado
Instrucciones de instalación
Instalación de Python:

Descarga e instala Python.
Asegúrate de marcar la opción "Add Python to PATH" durante la instalación.
Clonar el repositorio o descargar los archivos del proyecto:

Usa Git:
bash
Copiar código
git clone https://github.com/usuario/mate-exploradores.git
cd mate-exploradores
Alternativamente, descarga los archivos como ZIP y extráelos en una carpeta de tu elección.
Instalar dependencias necesarias:

Abre una terminal en la carpeta del proyecto y ejecuta:
bash
Copiar código
pip install pillow
Esta dependencia es opcional y se utiliza para la visualización de imágenes en el juego.
Ejecución del juego
Iniciar el juego:
En la terminal, navega a la carpeta donde se encuentra el archivo principal del juego (por ejemplo, mate_exploradores.py) y ejecuta:
bash
Copiar código
python mate_exploradores.py
Uso del programa
Pantalla de inicio:

Ingresa el nombre del jugador para personalizar la experiencia.
Selecciona un tema entre sumas, restas, multiplicaciones o divisiones.
Juego en curso:

Elige una categoría y responde preguntas. Cada respuesta correcta otorga puntos, mientras que una respuesta incorrecta resta una vida.
Al perder todas las vidas, el juego permite reiniciar el nivel o cambiar de tema.
Progreso y puntaje:

El sistema guarda automáticamente el progreso del jugador en la base de datos SQLite.
Puedes ver tu puntaje y el tema actual en cualquier momento.
Estructura del proyecto
mate_exploradores.py: Archivo principal del juego.
database.db: Archivo SQLite que almacena el progreso del jugador.
assets/: Carpeta opcional para recursos como imágenes o sonidos.
Respaldo y seguridad de datos
El progreso del jugador se guarda localmente en database.db. Cada vez que el jugador termina una partida, se realiza automáticamente un respaldo del archivo.

Contribuciones
Este proyecto es open-source bajo la licencia MIT. Si deseas contribuir, por favor abre un issue o envía un pull request en el repositorio.

Créditos
Desarrollado por un grupo de estudiantes de la Universidad Nacional, orientado a ayudar a niños de zonas rurales a mejorar en matemáticas.
