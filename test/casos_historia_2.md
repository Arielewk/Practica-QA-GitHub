# Casos de Prueba - HU-002: Inicio de Sesión

---

# TC-003

## Título
Inicio de sesión exitoso.

## Objetivo
Validar que un usuario registrado pueda iniciar sesión correctamente utilizando credenciales válidas.

## Precondiciones

- La plataforma SAFEZONE debe estar disponible.
- El usuario debe estar registrado previamente.
- Debe existir conexión con la base de datos.

## Datos de prueba

| Campo | Valor |
|--------|-------|
| Correo electrónico | juan.perez@gmail.com |
| Contraseña | Juan2025 |

## Pasos

1. Ingresar a la pantalla de inicio de sesión.
2. Escribir un correo electrónico registrado.
3. Ingresar la contraseña correcta.
4. Presionar el botón **Iniciar sesión**.

## Resultado esperado

- El sistema valida las credenciales.
- El usuario inicia sesión correctamente.
- Se registra el acceso exitoso.
- El usuario es redirigido a la pantalla principal.
- La sesión permanece activa mientras utiliza la aplicación.

## Resultado obtenido

Pendiente de ejecución.

## Estado

Pendiente

## Notas / Evidencias

Pendiente de agregar capturas de pantalla o registros de ejecución.

---

# TC-004

## Título
Intento de inicio de sesión con credenciales incorrectas.

## Objetivo
Validar que el sistema impida el acceso cuando el usuario ingrese credenciales inválidas.

## Precondiciones

- La plataforma SAFEZONE debe estar disponible.
- Debe existir un usuario registrado con el correo **juan.perez@gmail.com**.

## Datos de prueba

| Campo | Valor |
|--------|-------|
| Correo electrónico | juan.perez@gmail.com |
| Contraseña | Contraseña123 |

## Pasos

1. Ingresar a la pantalla de inicio de sesión.
2. Escribir un correo electrónico registrado.
3. Ingresar una contraseña incorrecta.
4. Presionar el botón **Iniciar sesión**.

## Resultado esperado

- El sistema valida las credenciales contra la base de datos.
- El acceso es rechazado.
- Se muestra un mensaje indicando que el correo electrónico o la contraseña son incorrectos.
- El usuario permanece en la pantalla de inicio de sesión.
- No se crea una sesión de usuario.

## Resultado obtenido

Pendiente de ejecución.

## Estado

Pendiente

## Notas / Evidencias

Pendiente de agregar capturas de pantalla o registros de ejecución.
