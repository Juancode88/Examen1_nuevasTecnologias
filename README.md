markdown
Copy
# Proyecto de Manejo de Archivos Excel con Python

Este proyecto consiste en un script de Python que realiza operaciones básicas con archivos Excel utilizando la biblioteca `openpyxl`. El script incluye la creación de un archivo Excel, la modificación de su contenido y un ejercicio que permite al usuario ingresar datos de estudiantes y guardar los nombres de los aprobados en un archivo Excel.

## Requisitos

- Python 3.x
- Entorno virtual de Python

## Instalación

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   cd tu-repositorio
Crear y activar un entorno virtual:

Windows:

bash
Copy
python -m venv venv
.\venv\Scripts\activate
macOS/Linux:

bash
Copy
python3 -m venv venv
source venv/bin/activate
Instalar dependencias:

bash
Copy
pip install openpyxl
Uso
El proyecto contiene un script llamado main.py que realiza las siguientes operaciones:

Crear un archivo Excel básico:

Crea un archivo Excel llamado mi_primer_excel.xlsx con algunas celdas predefinidas.

Leer y modificar el archivo Excel:

Lee el contenido del archivo mi_primer_excel.xlsx y modifica una celda.

Ejercicio de estudiantes aprobados:

Solicita al usuario que ingrese 3 nombres de estudiantes y sus notas.

Guarda los nombres de los estudiantes aprobados (nota >= 60) en un archivo Excel llamado ejercicio2.xlsx.

Ejecución del Script
Para ejecutar el script, asegúrate de que el entorno virtual esté activado y ejecuta:

bash
Copy
python main.py
Estructura del Proyecto
Copy
tu-repositorio/
│
├── main.py                # Script principal
├── README.md              # Documentación del proyecto
├── mi_primer_excel.xlsx   # Archivo Excel generado (después de la ejecución)
├── ejercicio2.xlsx        # Archivo Excel con estudiantes aprobados (después de la ejecución)
└── venv/                  # Entorno virtual (no incluido en el repositorio)
Contribución
Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

Haz un fork del repositorio.

Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).

Realiza tus cambios y haz commit (git commit -am 'Añade nueva funcionalidad').

Haz push a la rama (git push origin feature/nueva-funcionalidad).

Abre un Pull Request.
