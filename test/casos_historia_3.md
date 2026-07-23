# Casos de Prueba - HU-003: Reportar Incidente de Seguridad

---

# TC-005

## Título
Registro exitoso de un incidente de seguridad.

## Objetivo
Validar que un usuario autenticado pueda reportar correctamente un incidente de seguridad con información válida.

## Precondiciones

- La plataforma SAFEZONE debe estar disponible.
- El usuario debe haber iniciado sesión.
- Debe existir conexión con la base de datos.

## Datos de prueba

| Campo | Valor |
|--------|-------|
| Tipo de incidente | Robo |
| Descripción | Se reportó el robo de una motocicleta en el parque central. |
| Ubicación | Parque Central |
| Evidencia | foto_robo.jpg |

## Pasos

1. Iniciar sesión en la plataforma.
2. Acceder a la opción **Reportar Incidente**.
3. Seleccionar el tipo de incidente.
4. Escribir la descripción del incidente.
5. Indicar la ubicación donde ocurrió.
6. Adjuntar una evidencia (opcional).
7. Presionar el botón **Enviar Reporte**.

## Resultado esperado

- El sistema valida los datos ingresados.
- El reporte se almacena correctamente en la base de datos.
- Se registra la fecha y hora del reporte.
- Se muestra un mensaje indicando que el reporte fue enviado exitosamente.
- El incidente queda disponible para su visualización por otros usuarios.

## Resultado obtenido

Pendiente de ejecución.

## Estado

Pendiente

## Notas / Evidencias

Pendiente de agregar capturas de pantalla o registros de ejecución.

---

# TC-006

## Título
Intento de registrar un incidente sin completar los campos obligatorios.

## Objetivo
Validar que el sistema impida registrar un incidente cuando faltan datos obligatorios.

## Precondiciones

- La plataforma SAFEZONE debe estar disponible.
- El usuario debe haber iniciado sesión.

## Datos de prueba

| Campo | Valor |
|--------|-------|
| Tipo de incidente | Robo |
| Descripción | *(Vacía)* |
| Ubicación | *(Vacía)* |
| Evidencia | Ninguna |

## Pasos

1. Iniciar sesión en la plataforma.
2. Acceder a la opción **Reportar Incidente**.
3. Seleccionar el tipo de incidente.
4. Dejar vacíos los campos de descripción y ubicación.
5. Presionar el botón **Enviar Reporte**.

## Resultado esperado

- El sistema detecta que existen campos obligatorios sin completar.
- El reporte no se almacena en la base de datos.
- Se muestra un mensaje indicando que es necesario completar los campos obligatorios.
- El usuario permanece en el formulario de reporte para corregir la información.

## Resultado obtenido

Pendiente de ejecución.

## Estado

Pendiente

## Notas / Evidencias

Pendiente de agregar capturas de pantalla o registros de ejecución.
