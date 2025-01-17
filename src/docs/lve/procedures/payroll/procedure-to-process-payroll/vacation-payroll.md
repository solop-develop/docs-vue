---
title: Nómina Vacaciones
icon: app
category: Localización Venezuela
star: 9
sticky: 9
tag:

  - Procedimientos
  - Gestión de Nóminas
  - Procedimiento para Procesar Nómina
article: false
---

**Nómina Vacaciones**
========================

Para procesar una “**Nómina de Vacaciones**” debemos realizar el proceso de nómina estándar mencionado en el documento ''Procedimiento para procesarn ómina'' elaborado por [ERPyA](http://erpya.com). En esta ventana se registran los datos principales que ADempiere requiere para crear una nómina de vacaciones, cada uno de los campos detallados a continuación son relevantes para obtener un registro exitoso:

Estatus del Documento:

Seleccione “**Nómina Vacaciones**” en el campo “**Tipo de Documento**”

El tipo de documento le permitirá definir la acción del documento que esté registrando en ADempiere.

Seleccione “**Nómina Vacaciones**” en el campo “**Nómina**”

La nómina de vacaciones define el comportamiento de la nómina, para este caso por ser una nómina especial cuenta con las siguientes características:

Regla de Pago: Débito Directo
Contrato de Nómina: Contrato Mensual
Cargo: Vacaciones por Pagar

Seleccione la fecha en la qué esté ejecutando la nómina en el campo "**Fecha Contable**"

Seleccione el “**Socio de Negocio Empleado**” a quién se le procesa la nómina de vacaciones en el campo "**Socio de Negocio**"

Si son vacaciones colectivas a todo el personal no debe seleccionar ningún socio de negocio, deje este campo en blanco para que le procese la nómina de vacaciones a todo el personal.

![Nómina Vacaciones](/assets/img/docs/lve/procedures/payroll/procedures-to-process-payroll/resources/vacaciones2.png)

Imagen 1. Nómina de Vacaciones

Está nómina  por ser una nómina especial no debe registrarse con período

Incidencias:

Para está nómina es obligatorio registrar la incidencia llamada "**Fecha de Inicio de Vacaciones**" para conocer el día a partir del cúal saldrá de vacaciones el empleado y el sistema pueda calcular su fecha de regreso, cabe destacar que esta incidencia debe registrarse al socio de negocio empleado al cual se le procesará la nómina de vacaciones

|           **INCIDENCIA**                              |     **CÓDIGO**       |    **TIPO**    |
|-------------------------------------------------------|----------------------|----------------|
| Fecha de Inicio de Vacaciones                         |     ("IN_FIV")       |     Fecha      |

![Incidencia Nómina Vacaciones](/assets/img/docs/lve/procedures/payroll/procedures-to-process-payroll/resources/incidenciavacaciones1.png)

Imagen 2. Incidencia Vacaciones

Resultados:

- "**Reportes**"

Para visualizar los reportes de nóminas  puede seguir los pasos que se encuentran en el documento ''Reporte de nómina'' con los datos adicionales que se indican a continuación para cada reporte

- “**Recibo de Pago**”

- **Nómina**: Nómina de Vacaciones

- **Proceso de Nómina**: Ubique el número de documento del proceso de nómina que está ejecutando.

- **Configuración de Reporte de Nómina**: Vacaciones

![Recibo de Pago Nómina Vacaciones](/assets/img/docs/lve/procedures/payroll/procedures-to-process-payroll/resources/recibovacaciones.png)

Imagen 3. Recibo de Pago Nómina Vacaciones

- “**Detalle de Pago**”

- **Nómina**: Nómina de Vacaciones

- **Proceso de Nómina**: Ubique el número de documento del proceso de nómina que está ejecutando.

- **Configuración de Reporte de Nómina**: Vacaciones

- **Plantilla de Reporte de Nómina**: Detalle de Pago

![Detalle de Pago Nómina Vacaciones](/assets/img/docs/lve/procedures/payroll/procedures-to-process-payroll/resources/detallevacaciones.png)

Imagen 4. Detalle de Pago Nómina de Vacaciones

- “**Resumen de Pago**”

- **Nómina**: Nómina de Vacaciones

- **Proceso de Nómina**: Ubique el número de documento del proceso de nómina que está ejecutando.

- **Configuración de Reporte de Nómina**: Vacaciones

- **Plantilla de Reporte de Nómina**: Resumen de Pago

![Resumen de Pago Nómina Vacaciones](/assets/img/docs/lve/procedures/payroll/procedures-to-process-payroll/resources/resumenvacaciones.png)

Imagen 5. Resumen de Pago Nómina de Nómina de Vacaciones

- “**Retenciones**”

- **Nómina**: Nómina de Vacaciones

- **Proceso de Nómina**: Ubique el número de documento del proceso de nómina que está ejecutando.

- **Configuración de Reporte de Nómina**: Retenciones Parafiscales

![Retenciones Nómina Vacaciones](/assets/img/docs/lve/procedures/payroll/procedures-to-process-payroll/resources/retencionesvacaciones.png)

Imagen 6. Retenciones de Nómina de Vacaciones

- “**Aportes**”

- **Nómina**: Nómina de Vacaciones

- **Proceso de Nómina**: Ubique el número de documento del proceso de nómina que está ejecutando.

- **Configuración de Reporte de Nómina**: Aportes Parafiscales

![Aportes Nómina Vacaciones](/assets/img/docs/lve/procedures/payroll/procedures-to-process-payroll/resources/aportesvacaciones.png)

Imagen 7. Aportes Nómina de Vacaciones

Cabe destacar que los reportes de Aportes y Retenciones se deben pasar al Departamento de Contabilidad
