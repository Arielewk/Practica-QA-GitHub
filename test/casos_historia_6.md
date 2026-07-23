# Casos de Prueba - HU-006: Gestión de Perfil de Usuario

---

# TC-011

## Título
Actualización exitosa de la información del perfil.

## Objetivo
Validar que un usuario registrado pueda modificar y guardar correctamente la información de su perfil.

## Precondiciones

- La plataforma SAFEZONE debe estar disponible.
- El usuario debe haber iniciado sesión.
- El usuario debe tener un perfil previamente registrado.

## Datos de prueba

| Campo | Valor |
|--------|-------|
| Nombre | Juan Carlos |
| Apellido | Pérez López |
| Correo electrónico | juan.perez@gmail.com |
| Contraseña | Juan2025 |

## Pasos

1. Iniciar sesión en la plataforma.
2. Acceder al módulo **Mi Perfil**.
3. Modificar el nombre y el apellido.
4. Presionar el botón **Guardar cambios**.
5. Cerrar sesión.
6. Iniciar sesión nuevamente.
7. Acceder nuevamente al perfil del usuario.

## Resultado esperado

- El sistema valida la información ingresada.
- Los cambios se almacenan correctamente.
- Se muestra un mensaje de confirmación indicando que el perfil fue actualizado exitosamente.
- La información modificada se refleja inmediatamente.
- Los cambios permanecen después de cerrar e iniciar sesión nuevamente.

## Resultado obtenido

Pendiente de ejecución.

## Estado

Pendiente

## Notas / Evidencias

Pendiente de agregar capturas de pantalla o registros de ejecución.

---

# TC-012

## Título
Intento de actualizar el perfil con información inválida.

## Objetivo
Validar que el sistema impida guardar cambios cuando los datos ingresados no cumplen las validaciones establecidas.

## Precondiciones

- La plataforma SAFEZONE debe estar disponible.
- El usuario debe haber iniciado sesión.
- El usuario debe tener un perfil previamente registrado.

## Datos de prueba

| Campo | Valor |
|--------|-------|
| Nombre | Juan |
| Apellido | Pérez |
| Correo electrónico | juancorreo.com |
| Contraseña | 123 |

## Pasos

1. Iniciar sesión en la plataforma.
2. Acceder al módulo **Mi Perfil**.
3. Ingresar un correo electrónico con formato inválido.
4. Ingresar una contraseña que no cumpla los requisitos establecidos.
5. Presionar el botón **Guardar cambios**.

## Resultado esperado

- El sistema detecta que los datos ingresados son inválidos.
- No se guardan los cambios realizados.
- Se muestran mensajes indicando los errores encontrados.
- La información original del perfil permanece sin modificaciones.

## Resultado obtenido

Pendiente de ejecución.

## Estado

Pendiente

## Notas / Evidencias

Pendiente de agregar capturas de pantalla o registros de ejecución.
