# ABM Empleados

**ABM Empleados** es una aplicación web para la gestión de empleados, desarrollada utilizando Bootstrap y JavaScript. Los datos de los empleados se obtienen de una API simulada (MOCK API).

## Enlace a la Aplicación

Puedes probar la aplicación en [Netlify](https://simpleabm.netlify.app/).

## Estructura del Proyecto

### Archivo `services.js`

En el archivo `services.js`, encontrarás las funciones responsables de realizar los siguientes llamados a la API:

- Obtener datos de empleados
- Registrar un nuevo empleado
- Editar los datos de un empleado
- Eliminar un empleado específico (fila)
- Eliminar todos los empleados

### Archivo `core.js`

En el archivo `core.js`, se incluyen funciones para:

- Validaciones de datos
- Construcción del objeto empleado
- Creación y gestión de la tabla de empleados
- Filtro de empleados en la tabla
- Gestión de modales para edición y eliminación de empleados
- Implementación de la eliminación masiva de empleados
- Selección y deselección de todos los checkboxes desde el encabezado de la tabla

## Instalación y Ejecución en Desarrollo

Para ejecutar el proyecto en tu entorno local, sigue estos pasos:

1. **Clona el Repositorio**

   ```
   git clone https://github.com/tu-usuario/abm-empleados.git
   cd abm-empleados
   ```
2. **Instala las Dependencias**
    ```
    npm install
    ```

4. **Ejecuta el Servidor de Desarrollo**
   ```
   npm start
   ```

