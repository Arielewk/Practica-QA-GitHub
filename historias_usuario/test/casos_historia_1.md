# Casos de Prueba - HU-001: Registro de Usuario

---

# TC-001

## Título
Registro exitoso de un nuevo usuario.

## Objetivo
Validar que un ciudadano pueda registrarse correctamente en la plataforma SAFEZONE utilizando datos válidos.

## Precondiciones
- La plataforma SAFEZONE debe estar disponible.
- El usuario no debe tener una cuenta registrada previamente.
- Debe existir conexión con la base de datos.

## Datos de prueba

| Campo | Valor |
|--------|-------|
| Nombre | Juan |
| Apellido | Pérez |
| Correo | juan.perez@gmail.com |
| Contraseña | Juan2025 |

## Pasos

1. Ingresar a la pantalla de registro.
2. Escribir el nombre.
3. Escribir el apellido.
4. Ingresar un correo electrónico válido.
5. Escribir una contraseña con al menos ocho caracteres que contenga letras y números.
6. Presionar el botón **Registrarse**.

## Resultado esperado

- El sistema valida correctamente la información.
- Los datos se almacenan en la base de datos.
- Se muestra el mensaje **"Registro exitoso."**
- El usuario puede iniciar sesión utilizando las credenciales registradas.

## Resultado obtenido

Pendiente de ejecución.

## Estado

Pendiente

## Notas / Evidencias

Pendiente de agregar capturas de pantalla o registros de ejecución.

---

# TC-002

## Título
Intento de registro con un correo electrónico ya registrado.

## Objetivo
Validar que el sistema impida registrar un usuario cuando el correo electrónico ya existe.

## Precondiciones

- La plataforma SAFEZONE debe estar disponible.
- Debe existir previamente un usuario registrado con el correo **juan.perez@gmail.com**.

## Datos de prueba

| Campo | Valor |
|--------|-------|
| Nombre | Juan |
| Apellido | Pérez |
| Correo | juan.perez@gmail.com |
| Contraseña | Juan2025 |

## Pasos

1. Ingresar a la pantalla de registro.
2. Completar todos los campos con los datos indicados.
3. Presionar el botón **Registrarse**.

## Resultado esperado

- El sistema verifica que el correo ya existe.
- No se crea una nueva cuenta.
- Se muestra un mensaje indicando que el correo electrónico ya se encuentra registrado.

## Resultado obtenido

Pendiente de ejecución.

## Estado

Pendiente

## Notas / Evidencias

Pendiente de agregar capturas de pantalla o registros de ejecución.
