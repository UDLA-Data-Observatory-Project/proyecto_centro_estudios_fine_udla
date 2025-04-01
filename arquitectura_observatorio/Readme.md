# Observatorio de Datos Comunitarios (ODC)

## Estructura General

### 1. Recolección de Datos
- **LimeSurvey**: Utilizamos LimeSurvey, que se puede instalar automáticamente en Hostinger, para crear formularios en línea que los centros comunitarios en salud pueden usar para ingresar datos fácilmente.
- **Scripts de Ingesta**: Pequeños programas en Python que envían los datos recolectados por LimeSurvey directamente a nuestra base de datos SQL alojada en la nube de Hostinger.

### 2. Almacenamiento de Datos
- **Base de Datos SQL (MySQL)**: Utilizamos MySQL, que es compatible con los servidores de Hostinger, para almacenar de manera segura y organizada toda la información recolectada. MySQL es como un gran cuaderno digital donde todo está bien ordenado.

### 3. Procesamiento de Datos
- **ETL (Extract, Transform, Load)**: Utilizamos procesos de ETL con Python para extraer los datos de LimeSurvey, limpiarlos y transformarlos para que sean útiles, y luego cargarlos en la base de datos.
- **Procedimientos Almacenados**: Programas dentro de la base de datos MySQL que ayudan a organizar y preparar los datos para su análisis.

### 4. Análisis y Visualización de Datos
- **Dashboard Interactivo**: Desarrollamos una página web con gráficos y tablas que muestra la información de manera clara y atractiva. Utilizamos tecnologías web como HTML, CSS, y JavaScript, y frameworks como React o Angular para crear este dashboard.
- **Consultas SQL**: Realizamos consultas SQL a la base de datos para obtener la información que necesitamos mostrar en el dashboard.

### 5. Seguridad y Gobernanza de Datos
- **Seguridad de Datos**: Implementamos medidas de seguridad como contraseñas y cifrado para proteger la información y asegurarnos de que solo las personas autorizadas puedan acceder a ella. Hostinger ofrece certificados SSL gratuitos y opciones de seguridad avanzadas.
- **Gobernanza de Datos**: Establecemos reglas y políticas para asegurar que los datos sean precisos, completos y se usen de manera adecuada.

## Resumen de las Macroestructuras

1. **Recolección de Datos**: Formularios creados con LimeSurvey y scripts de ingesta.
2. **Almacenamiento de Datos**: Base de datos SQL (MySQL) en la nube de Hostinger.
3. **Procesamiento de Datos**: ETL y procedimientos almacenados.
4. **Análisis y Visualización de Datos**: Dashboard interactivo y consultas SQL.
5. **Seguridad y Gobernanza de Datos**: Medidas de seguridad y políticas de gobernanza.

## Pasos de Ejecución del Proyecto

1. **Adquisición del Servidor**:
   - Contratar un plan de hosting web o VPS en Hostinger.

2. **Instalación de LimeSurvey**:
   - Utilizar el instalador automático de Hostinger para instalar LimeSurvey en el servidor.

3. **Configuración del Servidor**:
   - Instalar y configurar la base de datos MySQL.
   - Configurar el entorno de desarrollo con Python y otras herramientas necesarias.

4. **Desarrollo de Formularios Digitales**:
   - Crear formularios digitales en LimeSurvey para la recolección de datos.

5. **Desarrollo del Sistema de Ingesta de Datos**:
   - Implementar scripts en Python para enviar los datos de LimeSurvey a la base de datos SQL.

6. **Desarrollo del Dashboard Web**:
   - Crear una página web con HTML, CSS, JavaScript y frameworks como React o Angular.
   - Integrar el dashboard con la base de datos SQL para mostrar los datos.

7. **Implementación de Seguridad y Gobernanza**:
   - Configurar medidas de seguridad en Hostinger, incluyendo certificados SSL y autenticación de usuarios.
   - Establecer políticas de gobernanza de datos.

8. **Pruebas y Despliegue**:
   - Realizar pruebas de funcionalidad y seguridad.
   - Desplegar la plataforma en el servidor de Hostinger.

9. **Capacitación y Soporte**:
   - Capacitar al personal en el uso de la plataforma.
   - Proveer soporte técnico y mantenimiento continuo.

