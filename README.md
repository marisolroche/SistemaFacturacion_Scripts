# SistemaFacturacion_Scripts
💸 Sistema de Gestión de Gastos
Este proyecto es un sistema básico para la gestión de gastos personales, donde los usuarios pueden registrar sus gastos, asociarlos a categorías y manejar diferentes monedas.

📁 Estructura del Proyecto
/proyecto-gestion-gastos │ ├── /scripts │ ├── create_database.sql # Script para crear la base de datos y sus tablas │ └── seed_data.sql # Script con datos semilla (Monedas y Categorías) │ └── README.md # Documentación general del proyecto

🛠️ Requisitos
SQL Server (cualquier versión compatible con Transact-SQL)
SSMS (SQL Server Management Studio) o Azure Data Studio
Git y cuenta en GitHub
🧱 Modelo de Datos
El sistema contiene las siguientes tablas principales:

Usuarios: Información básica de los usuarios del sistema.
Monedas: Tipos de monedas disponibles.
Categorías: Clasificación de los gastos.
Gastos: Registro de todos los gastos realizados por los usuarios.
Presupuestos: Límites establecidos para controlar gastos por categoría y tiempo.
Las tablas están normalizadas y se relacionan por medio de claves foráneas, garantizando integridad y consistencia de los datos.

🧪 Instrucciones de uso
Clona el repositorio:
git clone https://github.com/marisolroche/SistemaFacturacion_Scripts.git
⚙️ Ejecución de los Scripts
Abre SQL Server Management Studio (SSMS) o Azure Data Studio.
Ejecuta el script create_database.sql ubicado en el archivo /dbgestiongastos.sql para crear la base de datos y sus tablas.
Luego ejecuta el script del arcchivo datos_semillaseed_data.sql para insertar los datos iniciales (monedas y categorías).
Asegúrate de tener seleccionada la base de datos creada antes de ejecutar seed_data.sql.