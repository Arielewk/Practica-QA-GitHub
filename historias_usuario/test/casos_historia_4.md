# Casos de Prueba - HU-004: Consultar Alertas de Seguridad

---

# TC-007

## Título
Consulta exitosa de alertas de seguridad.

## Objetivo
Validar que el usuario pueda visualizar correctamente las alertas de seguridad registradas en la plataforma.

## Precondiciones

- La plataforma SAFEZONE debe estar disponible.
- Deben existir alertas registradas en el sistema.
- El usuario debe estar autenticado.

## Datos de prueba

| Campo | Valor |
|--------|-------|
| Categoría | Robo |
| Ubicación | Centro de la ciudad |

## Pasos

1. Iniciar sesión en la plataforma.
2. Acceder al módulo **Consultar Alertas**.
3. Visualizar la lista de alertas disponibles.
4. Aplicar el filtro por categoría **Robo**.
5. Buscar alertas correspondientes al **Centro de la ciudad**.
6. Seleccionar una alerta para visualizar su información detallada.

## Resultado esperado

- El sistema muestra las alertas activas.
- Las alertas aparecen ordenadas desde la más reciente.
- Cada alerta presenta fecha, ubicación y descripción.
- El usuario puede consultar el detalle de la alerta seleccionada.
- La información es clara y comprensible.

## Resultado obtenido

Pendiente de ejecución.

## Estado

Pendiente

## Notas / Evidencias

Pendiente de agregar capturas de pantalla o registros de ejecución.

---

# TC-008

## Título
Consulta de alertas sin resultados para la búsqueda realizada.

## Objetivo
Validar que el sistema responda correctamente cuando no existan alertas que coincidan con los filtros de búsqueda.

## Precondiciones

- La plataforma SAFEZONE debe estar disponible.
- El usuario debe estar autenticado.

## Datos de prueba

| Campo | Valor |
|--------|-------|
| Categoría | Desastre Natural |
| Ubicación | Isla Desconocida |

## Pasos

1. Iniciar sesión en la plataforma.
2. Acceder al módulo **Consultar Alertas**.
3. Aplicar el filtro por la categoría **Desastre Natural**.
4. Buscar alertas para la ubicación **Isla Desconocida**.

## Resultado esperado

- El sistema realiza la búsqueda correctamente.
- No se muestran alertas debido a que no existen coincidencias.
- El sistema informa mediante un mensaje que no se encontraron resultados.
- La aplicación continúa funcionando normalmente y permite realizar una nueva búsqueda.

## Resultado obtenido

Pendiente de ejecución.

## Estado

Pendiente

## Notas / Evidencias

Pendiente de agregar capturas de pantalla o registros de ejecución.
