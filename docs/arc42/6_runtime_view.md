# 6. Vista de Ejecución

## Descripción

La vista de ejecución describe cómo los componentes del sistema interactúan durante su funcionamiento.

**Flujo de trabajo para la Gestión de Empleados**:
1. El usuario de RRHH accede al frontend y selecciona la opción para crear un perfil de empleado.
2. El frontend realiza una llamada a la API para almacenar los datos en la base de datos.
3. La base de datos guarda la información del empleado y confirma la operación.

**Flujo de trabajo para la Gestión de Ausencias**:
1. El empleado solicita una ausencia a través de la aplicación.
2. La API valida la solicitud y la envía al gerente para su aprobación.
3. El gerente aprueba o rechaza la solicitud, y la aplicación notifica al empleado.

## Diagrama de Secuencia (PlantUML)

![Diagrama de Secuencia](../diagrams/plantuml/sequence_leave_request.png)
